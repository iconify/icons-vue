<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="c7atyebze"><mask id="SVG0lseHh3I" width="24" height="24" x="0" y="0" maskUnits="userSpaceOnUse"><path class="py7ktqbvf"/><circle class="utmrllbfo"/></mask><g mask="url(#SVG0lseHh3I)" class="wil2krbkc"><path class="yjggph6vk"/></g><path class="efzqbb96b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:map-check-sharp" /></template>
<style>
.c7atyebze {
  fill: none;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.efzqbb96b {
  stroke: currentColor;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m14.75 17.75l1.75 1.75l3.5-3.75");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.utmrllbfo {
  cx: 17.5px;
  cy: 17.5px;
  r: 6px;
  fill: var(--svg-color--000, #000);
}

.wil2krbkc {
  stroke: currentColor;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yjggph6vk {
  d: path("m4.4 5.75l3.45-1.5L9 3.75l1.15.48l3.7 1.54l1.15.48l1.15-.5l3.45-1.5l1.15-.5v14l-1.15.5l-3.45 1.5l-1.15.5l-1.15-.48l-3.7-1.54L9 17.75l-1.15.5l-3.45 1.5l-1.15.5v-14zm4.6-2v14m6-11.5v14");
}

</style>
