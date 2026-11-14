<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qlfe15bvy"/><path class="cxilx5bmh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:rearview-mirror" /></template>
<style>
.cxilx5bmh {
  d: path("M9 8.5h6a2.5 2.5 0 0 1 2.5 2.5a2.5 2.5 0 0 1-2.5 2.5H9A2.5 2.5 0 0 1 6.5 11A2.5 2.5 0 0 1 9 8.5m3-4.75V8.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qlfe15bvy {
  d: path("m2.5 19l2-14.5q7.5-1.5 15 0l2 14.5q-9.5-1.5-19 0");
}

</style>
