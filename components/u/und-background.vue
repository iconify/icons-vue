<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGR3npfcKw)" class="r4i437pya"/><path class="ik6btublg"/><path class="abke--bbz"/><path class="np_dm3sgd"/><path class="cy750zbkd"/></g><defs><linearGradient id="SVGR3npfcKw" x1="12.002" x2="12.002" y1="4" y2="20" gradientUnits="userSpaceOnUse"><stop class="al32kp7ym"/><stop offset="1" class="ffke88bnl"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:und-background" /></template>
<style>
.abke--bbz {
  fill: var(--svg-color--fff, #fff);
  d: path("M19.5 4c-.966.58-2.146 1.73-2.146 3.48v5.565c0 1.97-1 5.91-5 5.91c-2.285 0-3.9-.15-4.955-.325A11.5 11.5 0 0 0 12.35 20c5.72 0 7.15-4.175 7.15-6.26z");
}

.al32kp7ym {
  stop-color: var(--svg-color--a41351, #a41351);
}

.cy750zbkd {
  fill: var(--svg-color--fff, #fff);
  d: path("M8.786 7.48c0-1.95-1.43-2.67-2.14-2.785v8.35c0 3.475 2.14 4.17 3.21 4.17c1.284 0 2.385-.695 2.86-1.04c-3.145.555-3.93-1.855-3.93-3.13z");
}

.ffke88bnl {
  stop-color: var(--svg-color--e0196c, #e0196c);
}

.ft5dv1b6b {
  fill: none;
}

.ik6btublg {
  fill: var(--svg-color--fff, #fff);
  d: path("M19.5 13.74V4c-3.43 0-4.285 2.785-4.285 4.175v5.215c0 4.175-5.24 5.22-7.86 5.22c2 1.11 4.17 1.39 5 1.39c5.715 0 7.145-4.175 7.145-6.26");
}

.np_dm3sgd {
  fill: var(--svg-color--fff, #fff);
  d: path("M4.5 13.045V4l2.145.7v8c0 3.335 2.38 4.4 3.57 4.515c-.57.28-1.665.35-2.145.35c-2.855 0-3.57-3.015-3.57-4.52");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

</style>
