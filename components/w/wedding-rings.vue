<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wdr0qjxed"/><path class="rtu8b9byv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:wedding-rings" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rtu8b9byv {
  d: path("M9 10.5a6 6 0 1 0 12 0a6 6 0 1 0-12 0");
}

.wdr0qjxed {
  d: path("M3 13.5a6 6 0 1 0 12 0a6 6 0 1 0-12 0");
}

</style>
