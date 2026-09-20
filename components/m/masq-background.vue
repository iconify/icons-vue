<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGaG6cMe7w)" class="r4i437pya"/><path class="xdglryb1s"/></g><defs><linearGradient id="SVGaG6cMe7w" x1="12" x2="12" y1="4" y2="20" gradientUnits="userSpaceOnUse"><stop class="erg-8lbed"/><stop offset="1" class="rq9_-xb6b"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:masq-background" /></template>
<style>
.erg-8lbed {
  stop-color: var(--svg-color--00c0ff, #00c0ff);
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

.rq9_-xb6b {
  stop-color: var(--svg-color--0188fe, #0188fe);
}

.xdglryb1s {
  fill: var(--svg-color--fff, #fff);
  d: path("M16.92 5.955c-2.583-2.607-7.255-2.607-9.839 0c-2.583 2.606-2.583 7.237 0 9.848l2.177 1.82v-1.67c0-.95.516-2.555 1.98-3.858q1.483-1.32 2.99-2.61l.059.118l-2.254 2.167c-.457.595-1.371 2.163-1.371 3.685c0 1.65.621 3.256 1.705 4.545l4.554-4.6a6.73 6.73 0 0 0 0-9.445");
}

</style>
