<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r4nz6hb4u"/><path class="nu66edblv"/><path class="p65z8acrr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:voice-record" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nu66edblv {
  d: path("M4 10.5v.5a6 6 0 0 0 12 0v-.5M10 17v4.5m-3 0h6");
}

.p65z8acrr {
  fill: currentColor;
  d: path("M17 5a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

.r4nz6hb4u {
  d: path("M10 2.5za3.25 3.25 0 0 1 3.25 3.25v4.5A3.25 3.25 0 0 1 10 13.5a3.25 3.25 0 0 1-3.25-3.25v-4.5A3.25 3.25 0 0 1 10 2.5");
}

</style>
