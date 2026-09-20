<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="mumfproca"/><path fill="url(#SVGBBzuFbhO)" class="jdmxeg3lj"/><path fill="url(#SVGastrUb3s)" class="lnjtw8twt"/><path class="tgsn3x8si"/></g><defs><linearGradient id="SVGBBzuFbhO" x1="18.25" x2="4.655" y1="11.542" y2="14.72" gradientUnits="userSpaceOnUse"><stop class="tvpuj8b9x"/><stop offset="1" class="e5ca-0brc"/></linearGradient><linearGradient id="SVGastrUb3s" x1="24.5" x2="6.998" y1="14.291" y2="14.456" gradientUnits="userSpaceOnUse"><stop offset=".36" class="bg2rzdb_t"/><stop offset=".66" class="yh2fp-dwt"/><stop offset="1" class="y0lk_ibnw"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:qrdo-background" /></template>
<style>
.bg2rzdb_t {
  stop-color: var(--svg-color--ff26eb, #ff26eb);
}

.e5ca-0brc {
  stop-color: var(--svg-color--ffe000, #ffe000);
}

.ft5dv1b6b {
  fill: none;
}

.jdmxeg3lj {
  d: path("M12 6.497a5.5 5.5 0 0 0-5.39 6.6a1.25 1.25 0 1 1-2.45.5a8 8 0 1 1 15.84-1.6h-2.5a5.5 5.5 0 0 0-5.5-5.5");
}

.lnjtw8twt {
  d: path("M18.4 9.5a1.25 1.25 0 0 1 1.46 1a8 8 0 0 1 .14 1.49v.004c0 2.04-.765 3.9-2.02 5.315l.485.585a1.25 1.25 0 1 1-1.93 1.59l-.485-.59A7.999 7.999 0 0 1 4 11.994h2.5a5.5 5.5 0 0 0 7.93 4.935l-.73-.885a1.25 1.25 0 0 1 1.93-1.59l.74.895a5.48 5.48 0 0 0 1.04-4.385a1.25 1.25 0 0 1 .995-1.46z");
}

.mumfproca {
  fill: var(--svg-color--000, #000);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.tgsn3x8si {
  fill: var(--svg-color--ffe000, #ffe000);
  d: path("M6.515 12.417q.029.351.095.68a1.25 1.25 0 1 1-2.45.5a8 8 0 0 1-.16-1.6h2.5");
}

.tvpuj8b9x {
  stop-color: var(--svg-color--2dde41, #2dde41);
}

.y0lk_ibnw {
  stop-color: var(--svg-color--27b3f9, #27b3f9);
}

.yh2fp-dwt {
  stop-color: var(--svg-color--137ff9, #137ff9);
}

</style>
