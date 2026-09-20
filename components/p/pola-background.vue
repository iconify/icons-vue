<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="sowberbqe"/><path class="d_fm04dnw"/><path class="nzbybkb_y"/><path class="ivmqlobqz"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:pola-background" /></template>
<style>
.d_fm04dnw {
  fill: var(--svg-color--fff, #fff);
  d: path("m13.882 19.53l-.847-1.412l2.024-3.765L12 9.177h1.573l3.133 5.176z");
}

.ft5dv1b6b {
  fill: none;
}

.ivmqlobqz {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.353 11.058H20l-3.957-6.582l-5.925-.006l.833 1.412h4.343z");
}

.nzbybkb_y {
  fill: var(--svg-color--fff, #fff);
  d: path("M5.647 12.94H4l3.957 6.583l5.925.006l-.832-1.412H8.706zm4.471-8.47l.846 1.412l-2.023 3.765L12 14.823h-1.573L7.294 9.647z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.sowberbqe {
  fill: var(--svg-color--1b7eff, #1b7eff);
  d: path("M24 0H0v24h24z");
}

</style>
