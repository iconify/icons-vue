<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGs6LnCbDO)" class="r4i437pya"/><path class="vxl_9lbrr"/></g><defs><linearGradient id="SVGs6LnCbDO" x1="7.007" x2="20.033" y1="9.749" y2="17.043" gradientUnits="userSpaceOnUse"><stop class="i4ly6mbjt"/><stop offset="1" class="ipenwjb2m"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:ptu-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.i4ly6mbjt {
  stop-color: var(--svg-color--0a68f4, #0a68f4);
}

.ipenwjb2m {
  stop-color: var(--svg-color--3dffb9, #3dffb9);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.vxl_9lbrr {
  fill: var(--svg-color--fff, #fff);
  d: path("M14.372 4H9.628a4.304 4.304 0 0 0-4.249 4.359V20h2.759V8.359c0-.993.513-1.6 1.49-1.6h4.744c.977 0 1.49.601 1.49 1.6V20h2.759V8.359A4.303 4.303 0 0 0 14.372 4");
}

</style>
