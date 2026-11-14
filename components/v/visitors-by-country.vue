<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="sihoylw_m"/><path class="pa7dp187k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:visitors-by-country" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pa7dp187k {
  d: path("M6.5 14a3 7 0 1 0 6 0a3 7 0 1 0-6 0m-4 0h14m1.5-3s-3.5-3-3.5-5.5a3.5 3.5 0 0 1 7 0C21.5 8 18 11 18 11");
}

.sihoylw_m {
  d: path("M2.5 14a7 7 0 1 0 14 0a7 7 0 1 0-14 0");
}

</style>
