<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/srej3pboq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="srej3pboq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uis:user-arrows" /></template>
