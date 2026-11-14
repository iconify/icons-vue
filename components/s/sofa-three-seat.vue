<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wle-f0bmt"/><path class="v5b567g-l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:sofa-three-seat" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v5b567g-l {
  d: path("M4 10V7.5A1.5 1.5 0 0 1 5.5 6h13A1.5 1.5 0 0 1 20 7.5V10M9.5 6v12m5-12v12");
}

.wle-f0bmt {
  d: path("M2.5 11.5a1.5 1.5 0 0 1 3 0v2h13v-2a1.5 1.5 0 0 1 3 0V18h-19Z");
}

</style>
