<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGbnkzM7dD)" class="r4i437pya"/><path class="jgs30bcxe"/><path class="nobhpuryo"/></g><defs><linearGradient id="SVGbnkzM7dD" x1="15.769" x2="4.13" y1="19.507" y2="15.154" gradientUnits="userSpaceOnUse"><stop class="uk2uxngyq"/><stop offset="1" class="lpyrqobec"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:zil-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.jgs30bcxe {
  fill: var(--svg-color--fff, #fff);
  d: path("M6.352 5.026L15.29 9.34l2.353-1.035L8.692 4z");
}

.lpyrqobec {
  stop-color: var(--svg-color--347181, #347181);
}

.nobhpuryo {
  fill: var(--svg-color--fff, #fff);
  d: path("M6.352 5.025v2.33l6.222 2.998l-6.222 3.045v2.296L15.294 20v-2.306l-6.057-2.941l6.057-3.106V9.34L6.352 5.035zm8.943 4.303l2.353-1.021v2.306l-2.353 1.026zm0 10.654l2.353-1.026V11.78l-2.353 1.035z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.uk2uxngyq {
  stop-color: var(--svg-color--60aaac, #60aaac);
}

</style>
