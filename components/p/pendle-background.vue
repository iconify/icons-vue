<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="gbqdlxb0c"/><path class="e65yutanh"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:pendle-background" /></template>
<style>
.e65yutanh {
  fill: var(--svg-color--fff, #fff);
  d: path("M7.917 15.244a4.4 4.4 0 0 0-2.576 1.211A7.96 7.96 0 0 1 4 12.02a8 8 0 0 1 3.917-6.88zm.981 0a4.4 4.4 0 0 1 3.89 4.737a8 8 0 1 0-3.89-15.338z");
}

.ft5dv1b6b {
  fill: none;
}

.gbqdlxb0c {
  fill: var(--svg-color--152e51, #152e51);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
