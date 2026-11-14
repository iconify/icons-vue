<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yx-22nbvv"/><path class="b4i_m0bvf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:range-cooker" /></template>
<style>
.b4i_m0bvf {
  d: path("M9.625 12.5h4.75A2.625 2.625 0 0 1 17 15.125v.75a2.625 2.625 0 0 1-2.625 2.625h-4.75A2.625 2.625 0 0 1 7 15.875v-.75A2.625 2.625 0 0 1 9.625 12.5M7.5 7.5h.01m2.99 0h.01m2.99 0h.01m2.99 0h.01");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yx-22nbvv {
  d: path("M7.5 3h9A3.5 3.5 0 0 1 20 6.5V18a3.5 3.5 0 0 1-3.5 3.5h-9A3.5 3.5 0 0 1 4 18V6.5A3.5 3.5 0 0 1 7.5 3");
}

</style>
