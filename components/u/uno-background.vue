<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGBN7WScUX)" class="r4i437pya"/><path class="d01lt-cfo"/><path class="u_3zcb9xx"/></g><defs><linearGradient id="SVGBN7WScUX" x1="9.575" x2="9.575" y1="6.667" y2="17.333" gradientUnits="userSpaceOnUse"><stop class="v4-w6wtkv"/><stop offset="1" class="f5zzelbzd"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:uno-background" /></template>
<style>
.d01lt-cfo {
  fill: var(--svg-color--fff, #fff);
  d: path("M5.94 6.667H4v6.787a3.88 3.88 0 0 0 3.879 3.879h.484a3.88 3.88 0 0 0 3.879-3.879V6.667h-1.94v6.545a2.182 2.182 0 0 1-4.363 0zm7.271 2.909h1.94v7.272h-1.94z");
}

.f5zzelbzd {
  stop-color: var(--svg-color--3e3bac, #3e3bac);
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

.u_3zcb9xx {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.333 9.332a2.666 2.666 0 0 0-2.666 2.666v4.849h.485v-4.364a1.455 1.455 0 0 1 2.909 0v4.364H20v-4.849a2.666 2.666 0 0 0-2.667-2.666");
}

.v4-w6wtkv {
  stop-color: var(--svg-color--5079dd, #5079dd);
}

</style>
