<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVG39enZdnu)" class="r4i437pya"/><path clip-rule="evenodd" class="rles-yban"/></g><defs><linearGradient id="SVG39enZdnu" x1="12" x2="12" y1="4" y2="20" gradientUnits="userSpaceOnUse"><stop class="i_a6_hxmb"/><stop offset="1" class="wxajg_2ob"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:tdrop-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.i_a6_hxmb {
  stop-color: var(--svg-color--00f2ff, #00f2ff);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.rles-yban {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M12 20a6.737 6.737 0 0 0 6.737-6.737C18.737 9.541 12.842 4 12 4s-6.737 5.541-6.737 9.263A6.736 6.736 0 0 0 12 20m-3.368-8v2.947h2.105v2.106h2.526v-2.106h2.105V12z");
}

.wxajg_2ob {
  stop-color: var(--svg-color--00bcf3, #00bcf3);
}

</style>
