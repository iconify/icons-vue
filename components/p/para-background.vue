<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGj44SieQF)" class="r4i437pya"/><path class="bq_1gub3a"/><path class="x7o2tawks"/></g><defs><linearGradient id="SVGj44SieQF" x1="3.998" x2="18.267" y1="12.145" y2="12.082" gradientUnits="userSpaceOnUse"><stop class="cl8wg8bua"/><stop offset="1" class="xofk90tyd"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:para-background" /></template>
<style>
.bq_1gub3a {
  fill: var(--svg-color--fff, #fff);
  d: path("m4.822 10.107l7.107 3.838c.35.19.78.19 1.13 0l6.123-3.313a1.51 1.51 0 0 0 0-2.684l-6.998-3.77a1.46 1.46 0 0 0-1.39 0l-5.977 3.25a1.51 1.51 0 0 0 0 2.679z");
}

.cl8wg8bua {
  stop-color: var(--svg-color--02daff, #02daff);
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

.x7o2tawks {
  fill: var(--svg-color--fff, #fff);
  d: path("m6.33 12.516l5.668 2.999c.375.2.835.2 1.2-.015l4.363-2.514l1.615.87a1.51 1.51 0 0 1 0 2.683l-6.118 3.314c-.35.19-.78.195-1.13 0L4.821 16.02a1.509 1.509 0 0 1-.005-2.684z");
}

.xofk90tyd {
  stop-color: var(--svg-color--5414f1, #5414f1);
}

</style>
