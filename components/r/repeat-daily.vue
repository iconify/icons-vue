<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="o9978pbip"/><path class="kx76gnhda"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:repeat-daily" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kx76gnhda {
  d: path("M15.75 8.75L18 11l2.25-2.25m-4 9.25a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0M18 14v1m0 6v1m-4-4h1m6 0h1");
}

.o9978pbip {
  d: path("M10.75 18A7.25 7.25 0 1 1 18 10.75");
}

</style>
