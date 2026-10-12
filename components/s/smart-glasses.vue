<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="w3zbspbur"/><rect class="d8uvdbb4t"/><path class="yslmh4b_x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:smart-glasses" /></template>
<style>
.d8uvdbb4t {
  width: 6.5px;
  height: 6.5px;
  x: 13.25px;
  y: 9.25px;
  rx: 2.25px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.w3zbspbur {
  width: 6.5px;
  height: 6.5px;
  x: 4.25px;
  y: 9.25px;
  rx: 2.25px;
}

.yslmh4b_x {
  d: path("M10.75 11.25a1.5 1.5 0 0 1 2.5 0m-9-.25l-1.5-3.75m17 3.75l1.5-3.75m-6 5.25h3");
}

</style>
