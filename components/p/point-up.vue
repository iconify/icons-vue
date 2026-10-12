<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wv7z-jxbt"/><path class="zrul9obkn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:point-up" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wv7z-jxbt {
  d: path("M10 12V4.25a1.25 1.25 0 0 1 2.5 0V10h1.75a2.5 2.5 0 0 1 2.5 2.5V16a5.25 5.25 0 0 1-5.25 5.25H11a4.5 4.5 0 0 1-4.5-4.5V14a2 2 0 0 1 2-2Zm2.5-1.5v3");
}

.zrul9obkn {
  d: path("M7 15.5c1.75-.5 3.5-.5 5.25.25");
}

</style>
