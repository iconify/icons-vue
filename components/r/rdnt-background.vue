<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGhdRTmcwk)" class="r4i437pya"/><path class="ih8ombcjj"/></g><defs><linearGradient id="SVGhdRTmcwk" x1="12" x2="12" y1="4" y2="20" gradientUnits="userSpaceOnUse"><stop class="lsi5-3j7d"/><stop offset="1" class="dtm-zib2w"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:rdnt-background" /></template>
<style>
.dtm-zib2w {
  stop-color: var(--svg-color--5a10f5, #5a10f5);
}

.ft5dv1b6b {
  fill: none;
}

.ih8ombcjj {
  fill: var(--svg-color--fff, #fff);
  d: path("M11 9.502L6 6l3.502 5L4 12l5.502 1L6 17.502l5-3.004L12 20l1-5.502l5.249 3.004L14 13l6-1l-6-1l4-5l-5 3.502L12 4z");
}

.lsi5-3j7d {
  stop-color: var(--svg-color--0fa, #0fa);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

</style>
