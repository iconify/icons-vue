<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVG0s4lDbwz)" class="r4i437pya"/><path class="s6p1-nbhk"/></g><defs><linearGradient id="SVG0s4lDbwz" x1="4" x2="19.153" y1="19.638" y2="2.35" gradientUnits="userSpaceOnUse"><stop class="l1p8ypbhf"/><stop offset=".15" class="dux3_ebyy"/><stop offset=".47" class="x-pclcc3l"/><stop offset=".74" class="hfiv3eb5b"/><stop offset="1" class="r3he05rto"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:vet-background" /></template>
<style>
.dux3_ebyy {
  stop-color: var(--svg-color--4163ad, #4163ad);
}

.ft5dv1b6b {
  fill: none;
}

.hfiv3eb5b {
  stop-color: var(--svg-color--54b1b6, #54b1b6);
}

.l1p8ypbhf {
  stop-color: var(--svg-color--582974, #582974);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r3he05rto {
  stop-color: var(--svg-color--86e931, #86e931);
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.s6p1-nbhk {
  fill: var(--svg-color--fff, #fff);
  d: path("M20 4.75h-1.43c-.35 0-.665.2-.82.515L14 13.035l-.005-.005l-1 2.07v.01l-1 2.07L7 6.825h1.425c.35 0 .67.2.82.515l3.265 6.715l1-2.07l-2.635-5.425a3.21 3.21 0 0 0-2.89-1.81H4l1 2.075l6 12.425h2z");
}

.x-pclcc3l {
  stop-color: var(--svg-color--22b2f9, #22b2f9);
}

</style>
