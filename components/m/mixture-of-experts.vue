<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xr9h6cbsf"/><path class="y_0d9c3hv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:mixture-of-experts" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xr9h6cbsf {
  d: path("M2.75 12a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0m4.5 0h8.25m1-7.75H12v15.5h4.5M18.25 2.5h.5a1.75 1.75 0 0 1 1.75 1.75A1.75 1.75 0 0 1 18.75 6h-.5a1.75 1.75 0 0 1-1.75-1.75a1.75 1.75 0 0 1 1.75-1.75");
}

.y_0d9c3hv {
  d: path("M18.125 9h.75a2.625 2.625 0 0 1 2.625 2.625v.75A2.625 2.625 0 0 1 18.875 15h-.75a2.625 2.625 0 0 1-2.625-2.625v-.75A2.625 2.625 0 0 1 18.125 9m.125 9h.5a1.75 1.75 0 0 1 1.75 1.75a1.75 1.75 0 0 1-1.75 1.75h-.5a1.75 1.75 0 0 1-1.75-1.75A1.75 1.75 0 0 1 18.25 18");
}

</style>
