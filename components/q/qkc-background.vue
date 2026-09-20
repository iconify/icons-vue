<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGCtgBBbDj)" class="r4i437pya"/><path class="x7-hocbpi"/></g><defs><linearGradient id="SVGCtgBBbDj" x1="12" x2="12" y1="5.998" y2="18.002" gradientUnits="userSpaceOnUse"><stop class="vuzcqlp8s"/><stop offset="1" class="a9r-a98hh"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:qkc-background" /></template>
<style>
.a9r-a98hh {
  stop-color: var(--svg-color--1b3586, #1b3586);
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.vuzcqlp8s {
  stop-color: var(--svg-color--39a3db, #39a3db);
}

.x7-hocbpi {
  fill: var(--svg-color--fff, #fff);
  d: path("M19.51 6.04a.8.8 0 0 0-.88.256l-3.882 4.701c-.705-.865-1.415-1.64-2.125-2.506a.8.8 0 0 0-.566-.29c-.425-.03-.685.29-.71.31c-.7.866-1.435 1.62-2.14 2.486L5.375 6.316c-.325-.3-.755-.38-1.05-.21c-.2.115-.29.3-.325.39v11.033c.02.04.15.325.485.435c.37.12.67-.09.7-.11l4.012-4.856c.77.935 1.54 1.77 2.31 2.706c.055.035.236.15.48.14a.85.85 0 0 0 .436-.15l2.325-2.696l3.642 4.381c.265.53.83.735 1.2.56c.33-.16.4-.585.41-.635V6.696a.72.72 0 0 0-.49-.655M5.495 15.499V8.497l3.001 3.536zm6.618-1.19a.2.2 0 0 1-.125.06c-.09.01-.15-.055-.166-.06c-.625-.76-1.2-1.525-1.825-2.285l1.76-2.276a1 1 0 0 1 .25-.04c.086.005.15.025.2.04l1.791 2.24zm6.387 1.19l-3.001-3.475l3-3.527z");
}

</style>
