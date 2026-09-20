<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGRaKXf7pZ)" class="r4i437pya"/><path class="zpk65-w5x"/><path class="h-5rcwb9k"/></g><defs><linearGradient id="SVGRaKXf7pZ" x1="17.412" x2="7.294" y1="5.882" y2="17.882" gradientUnits="userSpaceOnUse"><stop class="oqk-8e9wc"/><stop offset="1" class="dca7mp5ce"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:thor-background" /></template>
<style>
.dca7mp5ce {
  stop-color: var(--svg-color--08acfc, #08acfc);
}

.ft5dv1b6b {
  fill: none;
}

.h-5rcwb9k {
  fill: var(--svg-color--fff, #fff);
  d: path("m10.475 9.18l1.732 1.675L16.05 6.76l-5.576 2.414zm6.428-3.3l.273.368l-4.955 5.28l-2.575-2.494zm-2.88 8.03l-1.774-1.698l-4.607 4.78zm-7.2 3.972l-.263-.376l5.675-5.977l2.588 2.532z");
}

.oqk-8e9wc {
  stop-color: var(--svg-color--37faf9, #37faf9);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.zpk65-w5x {
  fill: var(--svg-color--fff, #fff);
  d: path("M20 12a8 8 0 1 1-16 0a8 8 0 0 1 16 0m-8 7.53a7.53 7.53 0 1 0 0-15.06a7.53 7.53 0 0 0 0 15.06");
}

</style>
