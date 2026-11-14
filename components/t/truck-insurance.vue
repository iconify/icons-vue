<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="sxr137edq"/><path class="fnd1yqbdz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:truck-insurance" /></template>
<style>
.fnd1yqbdz {
  d: path("m8.5 8.75l2.5 1v1.75c0 1.5-1 2.25-2.5 2.75C7 13.75 6 13 6 11.5V9.75Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.sxr137edq {
  d: path("M5.125 6.5h6.75A2.625 2.625 0 0 1 14.5 9.125v4.75a2.625 2.625 0 0 1-2.625 2.625h-6.75A2.625 2.625 0 0 1 2.5 13.875v-4.75A2.625 2.625 0 0 1 5.125 6.5M14.5 10H18l3.5 3.5v3h-7M5.25 19a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0m10.5 0a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0");
}

</style>
