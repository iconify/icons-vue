<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGGZpiiejD)" class="r4i437pya"/><path class="czun7j8ni"/></g><defs><linearGradient id="SVGGZpiiejD" x1="12" x2="11.845" y1="4" y2="30.979" gradientUnits="userSpaceOnUse"><stop class="c086qacie"/><stop offset="1" class="mg0u82bgi"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:sweth-background" /></template>
<style>
.c086qacie {
  stop-color: var(--svg-color--3068ef, #3068ef);
}

.czun7j8ni {
  fill: var(--svg-color--fff, #fff);
  d: path("m19.327 13.694l-.019.024l-.028.028l-5.544 5.53a2.475 2.475 0 0 1-3.496 0L8.71 17.75a.278.278 0 0 1 .114-.461a16.2 16.2 0 0 0 4-1.756q3.664-2.364 6.503-1.835zm-1.162-4.55c2.047.644 1.807 2.15 1.835 2.743c-2.24-1.176-4.937-.743-8.085 1.29c-2.353 1.52-4.315 2.146-5.9 1.882c-1.587-.268-1.944-2.207-2.015-2.72q2.61 1.322 7.007-1.515c2.73-1.765 5.11-2.325 7.158-1.68M13.74 4.72l1.435 1.44a.278.278 0 0 1-.14.466q-3.122.636-4.994 1.835c-2.14 1.384-3.962 2.024-5.468 1.93l5.666-5.666a2.475 2.475 0 0 1 3.496 0z");
}

.ft5dv1b6b {
  fill: none;
}

.mg0u82bgi {
  stop-color: var(--svg-color--1322ac, #1322ac);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

</style>
