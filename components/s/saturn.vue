<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="pfpt48slt"/><path class="xlifbgbxq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:saturn" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pfpt48slt {
  cx: 12px;
  cy: 12px;
  r: 5.5px;
}

.xlifbgbxq {
  d: path("M8.75 10h6.5m3.6 2.45a9.25 2.75 20 1 1-12.4-4.52");
}

</style>
