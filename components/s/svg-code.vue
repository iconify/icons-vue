<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="w_a5jubhp"/><path class="bw5fnkb2v"/><path class="xg9wykbzx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:svg-code" /></template>
<style>
.bw5fnkb2v {
  d: path("M13.5 2.5v4a2 2 0 0 0 2 2h4m-10.75 9c0-5 6.5 0 6.5-5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.w_a5jubhp {
  d: path("M7 2.5h6.5l6 6V19a2.5 2.5 0 0 1-2.5 2.5H7A2.5 2.5 0 0 1 4.5 19V5A2.5 2.5 0 0 1 7 2.5");
}

.xg9wykbzx {
  fill: currentColor;
  d: path("M8.75 16.25zA1.25 1.25 0 0 1 10 17.5a1.25 1.25 0 0 1-1.25 1.25A1.25 1.25 0 0 1 7.5 17.5a1.25 1.25 0 0 1 1.25-1.25m6.5-5za1.25 1.25 0 0 1 1.25 1.25a1.25 1.25 0 0 1-1.25 1.25A1.25 1.25 0 0 1 14 12.5a1.25 1.25 0 0 1 1.25-1.25");
}

</style>
