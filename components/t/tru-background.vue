<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="niooi3wsi"/><path clip-rule="evenodd" class="nm8hon5xe"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:tru-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.niooi3wsi {
  fill: var(--svg-color--1a5aff, #1a5aff);
  d: path("M24 0H0v24h24z");
}

.nm8hon5xe {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M13.185 9.872H10.63l-4.042 7.103L4 15.502l4.226-7.426a2.34 2.34 0 0 1 2.033-1.183h2.925zM7.659 6.893H4.254v3.404A3.404 3.404 0 0 0 7.66 6.893m7.186 1.185a2.34 2.34 0 0 1 2.036-1.185H20v2.979h-2.748l-3.435 6.05a2.34 2.34 0 0 1-2.035 1.185H8.509v-2.98h2.901zm3.453 7.326a1.702 1.702 0 1 0 0-3.403a1.702 1.702 0 0 0 0 3.403");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
