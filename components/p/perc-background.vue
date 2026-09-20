<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="u1sw1cb3e"/><path clip-rule="evenodd" class="vlr7mc_2b"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:perc-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.u1sw1cb3e {
  fill: var(--svg-color--009ba0, #009ba0);
  d: path("M24 0H0v24h24z");
}

.vlr7mc_2b {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M20 12a8 8 0 1 1-16 0a8 8 0 0 1 16 0m-1.412 0a6.588 6.588 0 1 1-13.176 0a6.588 6.588 0 0 1 13.176 0m-5.176 2.673v-7.85l1.411.777v7.732zm-4.236.024V6.842l1.412.777v7.732l-1.412-.66zm-1.882-3.483v2.79l1.412.622v-2.673l-1.412-.734zm8 0v2.79l1.412.622v-2.673l-1.412-.734zm-4-2.546v7.85l1.412.659V9.445z");
}

</style>
