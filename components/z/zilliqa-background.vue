<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGbnkzM7dD)" class="r4i437pya"/><path class="ol39h_a2i"/><path class="u9xt6w8mp"/></g><defs><linearGradient id="SVGbnkzM7dD" x1="15.769" x2="4.13" y1="19.507" y2="15.154" gradientUnits="userSpaceOnUse"><stop class="uk2uxngyq"/><stop offset="1" class="lpyrqobec"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:zilliqa-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.lpyrqobec {
  stop-color: var(--svg-color--347181, #347181);
}

.ol39h_a2i {
  fill: var(--svg-color--fff, #fff);
  d: path("M6.354 5.027L15.29 9.34l2.351-1.035L8.692 4z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.u9xt6w8mp {
  fill: var(--svg-color--fff, #fff);
  d: path("M6.354 5.027v2.33l6.22 2.997l-6.22 3.044v2.296L15.294 20v-2.306l-6.056-2.941l6.056-3.104V9.343l-8.94-4.307zm8.94 4.301l2.353-1.021v2.306l-2.353 1.025zm0 10.653l2.353-1.026V11.78l-2.353 1.034z");
}

.uk2uxngyq {
  stop-color: var(--svg-color--60aaac, #60aaac);
}

</style>
