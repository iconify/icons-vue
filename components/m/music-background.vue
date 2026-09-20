<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="tdqynnbjf"/><path class="v3707y8-k"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:music-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.tdqynnbjf {
  fill: var(--svg-color--fbbf02, #fbbf02);
  d: path("M24 0H0v24h24z");
}

.v3707y8-k {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.325 4.116A8 8 0 0 0 12 4.001a8 8 0 0 0-6.57 12.565c.55-.805 1.82-1.365 3.29-1.365c1.01 0 1.925.265 2.575.695zm4.25 2.155c1.385 3.055.17 4.69.17 4.69c-.935-2.82-3.65-3.235-3.65-3.235S12.3 17.35 12.3 17.476c0 1.04-1.105 1.92-2.61 2.184A8.003 8.003 0 0 0 20 12c0-2.25-.93-4.274-2.425-5.73");
}

</style>
