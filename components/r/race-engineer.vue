<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="eu-dnouck"/><path class="frb3xexin"/><path class="l9j2aacdh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:race-engineer" /></template>
<style>
.eu-dnouck {
  d: path("M7 9a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0M3.5 21.5c0-3 3-4.75 7-4.75c.767 0 1.496.064 2.175.189");
}

.frb3xexin {
  d: path("M16.5 10.5V9a6 6 0 0 0-12 0v3q0 2.5 2.5 2.5m10.25 0h2.5a1.75 1.75 0 0 1 1.75 1.75v3.5a1.75 1.75 0 0 1-1.75 1.75h-2.5a1.75 1.75 0 0 1-1.75-1.75v-3.5a1.75 1.75 0 0 1 1.75-1.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l9j2aacdh {
  d: path("M18 13.5h1a1 1 0 0 1 1 1a1 1 0 0 1-1 1h-1a1 1 0 0 1-1-1a1 1 0 0 1 1-1");
}

</style>
