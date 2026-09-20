<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGf9ZZserp)" class="r4i437pya"/><path class="ovrsc0bvf"/><path class="v0hs7g16v"/><path class="sfn4udy6g"/><path class="m7ukf3b3j"/></g><defs><linearGradient id="SVGf9ZZserp" x1="20" x2="12.009" y1="6.621" y2="15.849" gradientUnits="userSpaceOnUse"><stop class="rt3badzmy"/><stop offset="1" class="hgv5hacpq"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:nht-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.hgv5hacpq {
  stop-color: var(--svg-color--4c318d, #4c318d);
}

.m7ukf3b3j {
  fill: var(--svg-color--fff, #fff);
  d: path("M4.095 18H4V9.6A3.6 3.6 0 0 1 7.6 6H8c0 3.1 2.425 3.985 3.6 4h.705A3.63 3.63 0 0 1 16 13.62V14H8v.01A3.925 3.925 0 0 1 4.095 18");
}

.ovrsc0bvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M16 6.01c-.035 3.19-2.67 4-4 3.99l.005 3.435H20V6z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.rt3badzmy {
  stop-color: var(--svg-color--2f1e58, #2f1e58);
}

.sfn4udy6g {
  fill: var(--svg-color--fff, #fff);
  d: path("M8 14h8c-3.24 0-3.995 2.535-4 3.9c-.05-3.07-2.505-3.87-3.85-3.9zm4.02-4.19v.45H7.89V6.03h.35a3.78 3.78 0 0 1 3.78 3.78");
}

.v0hs7g16v {
  fill: var(--svg-color--fff, #fff);
  d: path("M16.26 18H12v-4h4V6h.355A3.635 3.635 0 0 1 20 9.585v4.635A3.815 3.815 0 0 1 16.26 18");
}

</style>
