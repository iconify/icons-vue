<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="h6_av1z1m"/><path class="sr4fullyh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:security-access-card" /></template>
<style>
.h6_av1z1m {
  d: path("M6 6h8a3.5 3.5 0 0 1 3.5 3.5V15a3.5 3.5 0 0 1-3.5 3.5H6A3.5 3.5 0 0 1 2.5 15V9.5A3.5 3.5 0 0 1 6 6");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.sr4fullyh {
  d: path("M9 7.75h2a.75.75 0 0 1 .75.75a.75.75 0 0 1-.75.75H9a.75.75 0 0 1-.75-.75a.75.75 0 0 1 .75-.75m-2.5 3H8a1.5 1.5 0 0 1 1.5 1.5v2a1.5 1.5 0 0 1-1.5 1.5H6.5a1.5 1.5 0 0 1-1.5-1.5v-2a1.5 1.5 0 0 1 1.5-1.5m5 1.25H15m-3.5 3H14m4.99-4.839a3.25 3.25 0 0 1 0 4.178m1.723-5.624a5.5 5.5 0 0 1 0 7.07");
}

</style>
