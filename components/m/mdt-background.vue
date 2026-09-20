<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="e66ygdtkl"/><path class="dl94b932a"/><path class="m5ld9-mvr"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:mdt-background" /></template>
<style>
.dl94b932a {
  fill: var(--svg-color--000, #000);
  d: path("M11.84 4.05L6.5 7.28c.195.165.385.61.42.71l4.58-2.81v3.395c0 .18.24.42.5.425c.26 0 .5-.25.5-.425V5.18L17.09 8c.075-.22.335-.63.41-.705a244 244 0 0 0-5.275-3.245c-.2-.08-.34-.035-.385 0m0 15.9L6.5 16.72a2.2 2.2 0 0 0 .42-.71l4.58 2.81v-3.395c0-.18.24-.42.5-.425c.26 0 .5.25.5.425v3.395L17.09 16c.075.22.335.63.41.705a244 244 0 0 1-5.275 3.245c-.2.08-.34.035-.385 0m-7.34-5.7V9.77c.57.19 1.24.08 1.5 0v4.48a2.53 2.53 0 0 0-1.5 0m13.5 0V9.77c.57.19 1.24.08 1.5 0v4.48a2.53 2.53 0 0 0-1.5 0m-6.98-1.76L6.28 9.65a2.27 2.27 0 0 0 .77-1.285l4.74 2.84a2.08 2.08 0 0 0-.77 1.285m2.02 0l4.745-2.84a2.27 2.27 0 0 1-.77-1.285l-4.745 2.84c.56.45.75 1.045.77 1.285m5.71-2.99a1.25 1.25 0 1 0 0-2.5a1.25 1.25 0 0 0 0 2.5m0 7.5a1.25 1.25 0 1 0 0-2.5a1.25 1.25 0 0 0 0 2.5m-13.5 0a1.25 1.25 0 1 0 0-2.5a1.25 1.25 0 0 0 0 2.5m0-7.5a1.25 1.25 0 1 0 0-2.5a1.25 1.25 0 0 0 0 2.5");
}

.e66ygdtkl {
  fill: var(--svg-color--bbe3ff, #bbe3ff);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.m5ld9-mvr {
  fill: var(--svg-color--000, #000);
  d: path("M11.99 13.26a1.25 1.25 0 1 0 0-2.5a1.25 1.25 0 0 0 0 2.5");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
