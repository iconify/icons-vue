<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="su8cspwgi"/><path class="n047z-buq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:rainbow-cloud" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.n047z-buq {
  d: path("M5.25 13.5A4.75 4.75 0 0 1 11.5 9");
}

.su8cspwgi {
  d: path("M10 19a2.8 2.8 0 0 1 .5-5.5A4 4 0 0 1 18 13a3 3 0 0 1 0 6Zm-8-5.5a8 8 0 0 1 14.25-5");
}

</style>
