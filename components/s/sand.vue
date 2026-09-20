<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r_55b89_m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r_55b89_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:sand" /></template>
