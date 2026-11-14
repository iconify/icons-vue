<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="e022up45g"/><path class="k2-9s7bzv"/><path class="y0hhkgc7t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:window-decal" /></template>
<style>
.e022up45g {
  d: path("M5.125 2.5h13.75A2.625 2.625 0 0 1 21.5 5.125v13.75a2.625 2.625 0 0 1-2.625 2.625H5.125A2.625 2.625 0 0 1 2.5 18.875V5.125A2.625 2.625 0 0 1 5.125 2.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k2-9s7bzv {
  d: path("M7 7h10v6.5L13.5 17H7Z");
}

.y0hhkgc7t {
  d: path("M17 13.5h-2.5a1 1 0 0 0-1 1V17m-8.75 2.25l1.5-1.5");
}

</style>
