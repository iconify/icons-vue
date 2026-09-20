<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGybajtcTO)" class="r4i437pya"/><path class="z9reptbqp"/></g><defs><linearGradient id="SVGybajtcTO" x1="6" x2="21.591" y1="3.286" y2="13.505" gradientUnits="userSpaceOnUse"><stop offset=".06" class="svuu6gb_h"/><stop offset="1" class="ygqosjbbg"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:rev-background" /></template>
<style>
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

.svuu6gb_h {
  stop-color: var(--svg-color--1a1c3c, #1a1c3c);
}

.ygqosjbbg {
  stop-color: var(--svg-color--720044, #720044);
}

.z9reptbqp {
  fill: var(--svg-color--fff, #fff);
  d: path("m9.59 4l7.258 4.121v3.394l-3.297 1.775l3.782 2.831V20l-6.788-5.09v-3.395l3.307-1.78L9.59 7.332v10.245L6.667 20V5.455L9.585 4z");
}

</style>
