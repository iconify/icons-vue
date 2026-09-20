<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGkArPPcfu)" class="r4i437pya"/><path class="wzivtxbzl"/><path class="nyj8cyauv"/></g><defs><linearGradient id="SVGkArPPcfu" x1="12" x2="12" y1="4" y2="19.999" gradientUnits="userSpaceOnUse"><stop class="bn2eh8yok"/><stop offset="1" class="zaoyf_b2t"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:moov-background" /></template>
<style>
.bn2eh8yok {
  stop-color: var(--svg-color--ff825f, #ff825f);
}

.ft5dv1b6b {
  fill: none;
}

.nyj8cyauv {
  fill: var(--svg-color--fff, #fff);
  d: path("M9.555 13.62v-3.243a.595.595 0 0 1 .889-.52l2.813 1.617a.6.6 0 0 1 0 1.04l-2.809 1.627a.595.595 0 0 1-.893-.52");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.wzivtxbzl {
  fill: var(--svg-color--fff, #fff);
  d: path("m10 4.08l8.595 5.066a.6.6 0 0 1 .293.516v4.693a.59.59 0 0 1-.293.515l-8.59 5.049a.58.58 0 0 1-.591 0L5.4 17.5a.6.6 0 0 1-.29-.515V6.942c0-.213.112-.409.294-.516L9.418 4.08a.57.57 0 0 1 .582 0M7.334 5.849v12.279c0 .177.195.293.35.204l10.644-6.16a.235.235 0 0 0 0-.404L7.68 5.644a.231.231 0 0 0-.346.205");
}

.zaoyf_b2t {
  stop-color: var(--svg-color--ff3e68, #ff3e68);
}

</style>
