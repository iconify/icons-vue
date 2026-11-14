<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ewxl7rbxc"/><path class="v7sd5nbsv"/><path class="tkqa5yb1g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:sewage-treatment-plant" /></template>
<style>
.ewxl7rbxc {
  d: path("M2.5 6A3.75 2 0 1 0 10 6a3.75 2 0 1 0-7.5 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.tkqa5yb1g {
  d: path("M13 14.5q2-1.5 4.25 0t4.25 0m-11.5 2h3");
}

.v7sd5nbsv {
  d: path("M2.5 6v12.5a3.75 2 0 0 0 7.5 0V6m3 5.5v7a2 2 0 0 0 2 2h4.5a2 2 0 0 0 2-2v-7");
}

</style>
