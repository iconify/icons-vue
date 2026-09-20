<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGW1YQntQK)" class="r4i437pya"/><path class="mxgsuzbhp"/></g><defs><linearGradient id="SVGW1YQntQK" x1="12" x2="12" y1="-.5" y2="24.5" gradientUnits="userSpaceOnUse"><stop class="iz18d3bnd"/><stop offset="1" class="a2zt197-f"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:swell-background" /></template>
<style>
.a2zt197-f {
  stop-color: var(--svg-color--3066ed, #3066ed);
}

.ft5dv1b6b {
  fill: none;
}

.iz18d3bnd {
  stop-color: var(--svg-color--2142cb, #2142cb);
}

.mxgsuzbhp {
  fill: var(--svg-color--fff, #fff);
  d: path("m19.328 13.695l-.02.02l-.03.03l-5.54 5.532a2.475 2.475 0 0 1-3.496 0l-1.53-1.527a.277.277 0 0 1 .113-.461q2.46-.759 3.998-1.753q3.662-2.367 6.505-1.841m-1.162-4.551c2.046.644 1.807 2.15 1.834 2.743q-3.36-1.762-8.086 1.291q-3.522 2.277-5.9 1.877C4.427 14.79 4.07 12.854 4 12.339q2.613 1.322 7.005-1.516q4.092-2.646 7.16-1.678m-4.428-4.421l1.437 1.435a.277.277 0 0 1-.14.468q-3.123.629-4.994 1.838q-3.207 2.074-5.467 1.927l5.668-5.668a2.475 2.475 0 0 1 3.496 0");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

</style>
