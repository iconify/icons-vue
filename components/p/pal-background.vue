<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVG5nTJGFkh)" class="r4i437pya"/><path class="jeywdybtl"/></g><defs><linearGradient id="SVG5nTJGFkh" x1="12" x2="12" y1="4" y2="20" gradientUnits="userSpaceOnUse"><stop class="vj-xel2co"/><stop offset="1" class="bhe328e3u"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:pal-background" /></template>
<style>
.bhe328e3u {
  stop-color: var(--svg-color--00d7af, #00d7af);
}

.ft5dv1b6b {
  fill: none;
}

.jeywdybtl {
  fill: var(--svg-color--fff, #fff);
  d: path("M9.66 12.842a.37.37 0 0 0-.16.279c-.002.655 0 1.304 0 1.957c0 .432-.283.608-.641.394c-1.204-.723-1.947-1.303-2.643-1.726A.5.5 0 0 1 6 13.354v-6.92c0-.143.098-.32.216-.391l3.281-1.989a.46.46 0 0 1 .435 0l3.341 1.989c.12.072.227.248.227.392v3.98a.52.52 0 0 1-.227.393c-1.115.675-2.498 1.358-3.612 2.034m4.84-1.948q.002-.98 0-1.958c0-.43.303-.608.66-.393c1.205.722 1.928 1.288 2.625 1.712a.5.5 0 0 1 .215.391v6.919c0 .144-.097.32-.216.392l-3.281 1.989a.46.46 0 0 1-.435 0l-3.333-1.989c-.119-.072-.235-.248-.235-.392v-3.98c0-.144.116-.32.235-.392c1.115-.675 2.51-1.344 3.624-2.02c.085-.05.141-.177.142-.28");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.vj-xel2co {
  stop-color: var(--svg-color--00edd8, #00edd8);
}

</style>
