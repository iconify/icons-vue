<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVG5JfVtcge)" class="r4i437pya"/><path class="a_qlaobyx"/></g><defs><linearGradient id="SVG5JfVtcge" x1="4" x2="20" y1="12" y2="12" gradientUnits="userSpaceOnUse"><stop class="yzcjzeb6o"/><stop offset="1" class="k4mpqtbvz"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:mkr-background" /></template>
<style>
.a_qlaobyx {
  fill: var(--svg-color--fff, #fff);
  d: path("M4.199 7.255a.4.4 0 0 1 .399-.002l6.398 3.64a.4.4 0 0 1 .203.347v5.16a.4.4 0 1 1-.8 0v-4.927L4.8 8.288V16.4a.4.4 0 0 1-.8 0V7.6a.4.4 0 0 1 .199-.345m15.602 0a.4.4 0 0 0-.399-.002l-6.398 3.64a.4.4 0 0 0-.203.347v5.16a.4.4 0 1 0 .8 0v-4.927L19.2 8.288V16.4a.4.4 0 0 0 .8 0V7.6a.4.4 0 0 0-.199-.345");
}

.ft5dv1b6b {
  fill: none;
}

.k4mpqtbvz {
  stop-color: var(--svg-color--586979, #586979);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.yzcjzeb6o {
  stop-color: var(--svg-color--1bc4a3, #1bc4a3);
}

</style>
