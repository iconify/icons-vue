<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGnjGBGdOj)" class="r4i437pya"/><path class="en4hbhrlp"/></g><defs><linearGradient id="SVGnjGBGdOj" x1="12" x2="12" y1="4" y2="20" gradientUnits="userSpaceOnUse"><stop class="q29ryybcc"/><stop offset="1" class="o24ughb8g"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:pxp-background" /></template>
<style>
.en4hbhrlp {
  fill: var(--svg-color--fff, #fff);
  d: path("M13 4h-2v1.5H6.5v2h1V18h-1v2h4v-2h-1v-3.5H11V16h2v-1.5c2.49-.02 4.5-2.04 4.5-4.5A4.526 4.526 0 0 0 13 5.5zm-3.5 8.5v-5h3.475A2.51 2.51 0 0 1 15.5 10c0 1.38-1.13 2.5-2.525 2.5z");
}

.ft5dv1b6b {
  fill: none;
}

.o24ughb8g {
  stop-color: var(--svg-color--057eff, #057eff);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.q29ryybcc {
  stop-color: var(--svg-color--5bc5f7, #5bc5f7);
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

</style>
