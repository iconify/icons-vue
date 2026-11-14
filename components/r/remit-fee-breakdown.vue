<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ghe12obwf"/><path class="zebqozphz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:remit-fee-breakdown" /></template>
<style>
.ghe12obwf {
  d: path("M5 2.5h14v19L16.75 20l-2.25 1.5L12 20l-2.5 1.5L7.25 20L5 21.5Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zebqozphz {
  d: path("M9.25 5.75h5.5a.75.75 0 0 1 .75.75a.75.75 0 0 1-.75.75h-5.5a.75.75 0 0 1-.75-.75a.75.75 0 0 1 .75-.75m0 4.25h3.5a.75.75 0 0 1 .75.75a.75.75 0 0 1-.75.75h-3.5a.75.75 0 0 1-.75-.75a.75.75 0 0 1 .75-.75m0 4.25h1.5a.75.75 0 0 1 .75.75a.75.75 0 0 1-.75.75h-1.5A.75.75 0 0 1 8.5 15a.75.75 0 0 1 .75-.75");
}

</style>
