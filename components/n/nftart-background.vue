<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVG0NtEyduY)" class="r4i437pya"/><path class="hhv03lbxx"/></g><defs><linearGradient id="SVG0NtEyduY" x1="4" x2="18.619" y1="7.217" y2="18.381" gradientUnits="userSpaceOnUse"><stop class="maxvamb_o"/><stop offset="1" class="obi04sphw"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:nftart-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.hhv03lbxx {
  fill: var(--svg-color--fff, #fff);
  d: path("M6.5 5v5.5H4v3h1.375c.65 0 .98-.83 1.125-1.585V19h3v-8.385L15.25 19h2.25v-5.5H20v-3h-1.375c-.65 0-.98.83-1.125 1.585V5h-3v8.48L8.7 5z");
}

.maxvamb_o {
  stop-color: var(--svg-color--d6022a, #d6022a);
}

.obi04sphw {
  stop-color: var(--svg-color--3c08c3, #3c08c3);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

</style>
