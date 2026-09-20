<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVG5ThHZdMh)" class="r4i437pya"/><path class="koqvnxb5i"/></g><defs><linearGradient id="SVG5ThHZdMh" x1="12" x2="12" y1="4.706" y2="19.294" gradientUnits="userSpaceOnUse"><stop class="jqur6ztqt"/><stop offset="1" class="jj4_pobll"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:strax-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.jj4_pobll {
  stop-color: var(--svg-color--10449e, #10449e);
}

.jqur6ztqt {
  stop-color: var(--svg-color--1b71bd, #1b71bd);
}

.koqvnxb5i {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.75 4.778a.47.47 0 0 1 .5 0l7.529 4.705a.47.47 0 0 1-.02.81l-7.528 4.235a.47.47 0 0 1-.462 0l-6.828-3.84v1.27L12 15.93l7.299-4.103a.472.472 0 0 1 .7.41v2.117a.47.47 0 0 1-.23.405l-7.53 4.47a.47.47 0 0 1-.47.005L4.24 14.999a.471.471 0 0 1 .461-.82l7.294 4.1l7.064-4.184v-1.059l-6.828 3.84a.47.47 0 0 1-.462 0L4.24 12.641a.47.47 0 0 1-.24-.41V9.88a.47.47 0 0 1 .221-.4l7.53-4.706zM5.394 9.86L12 13.578l6.607-3.718L12 5.733z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

</style>
