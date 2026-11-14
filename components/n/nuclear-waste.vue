<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="o9pb-jbhn"/><path class="rl0wapbcf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:nuclear-waste" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.o9pb-jbhn {
  d: path("M7.625 2.5h8.75A2.625 2.625 0 0 1 19 5.125v13.75a2.625 2.625 0 0 1-2.625 2.625h-8.75A2.625 2.625 0 0 1 5 18.875V5.125A2.625 2.625 0 0 1 7.625 2.5M5 5h14M5 19h14");
}

.rl0wapbcf {
  d: path("M11.25 10.75L10 8.5a4 4 0 0 1 4 0l-1.25 2.25a1.5 1.5 0 0 0-1.5 0M13.5 12H16a4 4 0 0 1-2 3.5l-1.25-2.25A1.5 1.5 0 0 0 13.5 12m-2.25 1.25L10 15.5A4 4 0 0 1 8 12h2.5a1.5 1.5 0 0 0 .75 1.25");
}

</style>
