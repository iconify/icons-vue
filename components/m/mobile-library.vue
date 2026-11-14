<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="k9lo38bum"/><path class="i2642_usd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:mobile-library" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i2642_usd {
  d: path("M5 19a2 2 0 1 0 4 0a2 2 0 1 0-4 0m10 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0m0-15.5V10h6.5m-16-2.5c2-.5 3.25 0 3.25 1c0-1 1.25-1.5 3.25-1V13c-2-.5-3.25 0-3.25 1c0-1-1.25-1.5-3.25-1Z");
}

.k9lo38bum {
  d: path("M2.5 17V5A1.5 1.5 0 0 1 4 3.5h11l6.5 6.5v7Z");
}

</style>
