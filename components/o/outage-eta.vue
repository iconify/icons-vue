<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="uv03l1lpc"/><path class="k_29nnbft"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:outage-eta" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k_29nnbft {
  d: path("M18 15.75V18l1.75 1");
}

.uv03l1lpc {
  d: path("M13.441 13.018L16 9.5h-5.5L12 2L3.5 12.5h6l-1.5 8l3.794-5.217M14 18a4 4 0 1 0 8 0a4 4 0 1 0-8 0");
}

</style>
