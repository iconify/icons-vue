<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rs_un_b_x"/><path class="n7-danb4h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:matka" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.n7-danb4h {
  d: path("M7 13.75c1.25-.8 2.5.8 3.75 0s2.5.8 3.75 0s1.75-.8 2.5 0");
}

.rs_un_b_x {
  d: path("M9.75 3h4.5a.75.75 0 0 1 0 1.5h-.5v2.6c2.9.9 4.75 3.65 4.75 7.15c0 4.1-2.8 7-6.5 7s-6.5-2.9-6.5-7c0-3.5 1.85-6.25 4.75-7.15V4.5h-.5a.75.75 0 0 1 0-1.5");
}

</style>
