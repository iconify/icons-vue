<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGMuOtecQK)" class="r4i437pya"/><path class="n6a99vb-t"/></g><defs><linearGradient id="SVGMuOtecQK" x1="11.999" x2="11.999" y1="18.604" y2="5.396" gradientUnits="userSpaceOnUse"><stop offset=".015" class="vozw4vt_u"/><stop offset=".26" class="w00jeebov"/><stop offset=".605" class="dvbvzjbsv"/><stop offset="1" class="c3qkfdbnr"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:xcad-background" /></template>
<style>
.c3qkfdbnr {
  stop-color: var(--svg-color--9b2aa6, #9b2aa6);
}

.dvbvzjbsv {
  stop-color: var(--svg-color--fc125f, #fc125f);
}

.ft5dv1b6b {
  fill: none;
}

.n6a99vb-t {
  fill: var(--svg-color--fff, #fff);
  d: path("m9.925 11.547l-2.97-6.15h4.299l1.513 3.602h.037l2.767-3.603H20l-5.328 6.41l3.159 6.797h-4.448l-1.626-4.138h-.037l-3.16 4.138H4z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.vozw4vt_u {
  stop-color: var(--svg-color--fd6422, #fd6422);
}

.w00jeebov {
  stop-color: var(--svg-color--fc194a, #fc194a);
}

</style>
