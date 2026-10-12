<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m5faclbjm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:snowboard-sharp" /></template>
<style>
.m5faclbjm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m19.6 4.4l1.949 1.949L19.42 8.46L8.46 19.42c-1.23 1.24-2.82 1.42-4.06.18s-1.06-2.83.18-4.06L15.54 4.58l2.111-2.129zm-8.13 2.12l6.01 6.01M6.52 11.47l6.01 6.01");
}

</style>
