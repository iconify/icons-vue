<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="h51x6nu8h"/><path class="cfc48-bcy"/><path class="r5cc7kbcr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:mud-pump" /></template>
<style>
.cfc48-bcy {
  fill: currentColor;
  d: path("M6 12.5a1 1 0 1 0 2 0a1 1 0 1 0-2 0");
}

.h51x6nu8h {
  d: path("M10 8.5a5 5 0 1 0 0 8");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.r5cc7kbcr {
  d: path("M7 8v9m4.75-8.5h3.5A1.75 1.75 0 0 1 17 10.25v4.5a1.75 1.75 0 0 1-1.75 1.75h-3.5A1.75 1.75 0 0 1 10 14.75v-4.5a1.75 1.75 0 0 1 1.75-1.75m6 2za.75.75 0 0 1 .75.75v2.5a.75.75 0 0 1-.75.75a.75.75 0 0 1-.75-.75v-2.5a.75.75 0 0 1 .75-.75m.75 2h3m0-2.25v4.5");
}

</style>
