<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vwchcybcm"/><path class="xther9roc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:working-hours-law" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vwchcybcm {
  d: path("m13.97 4.641l3.889 3.889a1.75 1.75 0 0 1 0 2.475l-.354.354a1.75 1.75 0 0 1-2.475 0L11.141 7.47a1.75 1.75 0 0 1 0-2.475l.354-.354a1.75 1.75 0 0 1 2.475 0M16 6.5l4.25-4.25m-4.5 15.25H20a1.5 1.5 0 0 1 1.5 1.5a1.5 1.5 0 0 1-1.5 1.5h-4.25a1.5 1.5 0 0 1-1.5-1.5a1.5 1.5 0 0 1 1.5-1.5M2 15.5a4.75 4.75 0 1 0 9.5 0a4.75 4.75 0 1 0-9.5 0");
}

.xther9roc {
  d: path("M6.75 13.5v2l1.75 1");
}

</style>
