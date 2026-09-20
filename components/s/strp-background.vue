<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGN5VO1bMU)" class="r4i437pya"/><path class="mmkoudbue"/><path class="uxpdgybit"/><path class="dh5uvobao"/></g><defs><linearGradient id="SVGN5VO1bMU" x1="4" x2="18.705" y1="13.717" y2="19.664" gradientUnits="userSpaceOnUse"><stop class="z682eibda"/><stop offset="1" class="nzzmtrekd"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:strp-background" /></template>
<style>
.dh5uvobao {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.49 15.48A7.6 7.6 0 0 0 19 10.914c0-1.53-.45-2.95-1.215-4.144A7.6 7.6 0 0 1 20 12.155c0 2.65-1.35 4.99-3.385 6.345a9.8 9.8 0 0 0 .875-3.02");
}

.ft5dv1b6b {
  fill: none;
}

.mmkoudbue {
  fill: var(--svg-color--fff, #fff);
  d: path("M6.5 17.5A7.6 7.6 0 0 1 4 11.845c0-2.65 1.35-4.99 3.385-6.345c-.41.915-.885 2.24-.885 3.31c0 1.77 1.5 4.55 4 5.06l.5-.76c.415.59 1.5 1.87 2.5 2.275a3.55 3.55 0 0 1-3.75 1.01l.25-.755a1.87 1.87 0 0 0-1.5-.76c-1 0-2 .76-2 2.025z");
}

.nzzmtrekd {
  stop-color: var(--svg-color--0c99d7, #0c99d7);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.uxpdgybit {
  fill: var(--svg-color--fff, #fff);
  d: path("M6.51 8.52A7.6 7.6 0 0 0 5 13.085c0 1.53.45 2.95 1.215 4.145A7.6 7.6 0 0 1 4 11.845c0-2.65 1.35-4.99 3.385-6.345a9.8 9.8 0 0 0-.875 3.02M17.5 6.5a7.6 7.6 0 0 1 2.5 5.655c0 2.65-1.35 4.99-3.385 6.345c.41-.915.885-2.24.885-3.31c0-1.77-1.5-4.55-4-5.06l-.5.76c-.415-.59-1.5-1.87-2.5-2.275a3.55 3.55 0 0 1 3.75-1.01L14 8.36c.165.25.7.76 1.5.76c1 0 2-.76 2-2.025z");
}

.z682eibda {
  stop-color: var(--svg-color--0367ab, #0367ab);
}

</style>
