<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gs6k2uf_m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gs6k2uf_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:tag" /></template>
