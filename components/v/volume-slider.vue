<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="akleju9by"/><circle class="a3xsjrbpo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:volume-slider" /></template>
<style>
.a3xsjrbpo {
  cx: 14.25px;
  cy: 18.5px;
  r: 2.25px;
}

.akleju9by {
  d: path("M7.25 6.5a.9.9 0 0 1 .9-.9h1.32l2.64-2.22a.54.54 0 0 1 .9.42v8.4a.54.54 0 0 1-.9.42L9.47 10.4H8.15a.9.9 0 0 1-.9-.9ZM16 6a3 3 0 0 1 0 4M3.75 18.5H12m4.5 0h3.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
