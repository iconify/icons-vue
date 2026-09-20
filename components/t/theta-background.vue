<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVG1RaTpbJv)" class="r4i437pya"/><path clip-rule="evenodd" class="mwrmy7bok"/><path class="bx9rc513u"/></g><defs><linearGradient id="SVG1RaTpbJv" x1="5.622" x2="18.698" y1="5.205" y2="18.973" gradientUnits="userSpaceOnUse"><stop class="qyx7slpkd"/><stop offset=".53" class="toy1_lbnc"/><stop offset="1" class="hdgq2zblw"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:theta-background" /></template>
<style>
.bx9rc513u {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.58 9.892H9.475v.842h5.052v-.842h-2.105V7.365h-.842zm0 4.21H9.475v-.842h5.052v.842h-2.105v2.526h-.842z");
}

.ft5dv1b6b {
  fill: none;
}

.hdgq2zblw {
  stop-color: var(--svg-color--2ee4be, #2ee4be);
}

.mwrmy7bok {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M16.21 4.842H7.79v14.316h8.42zm-9.263 0v14.316L7.79 20h8.421l.842-.842V4.842L16.21 4H7.79z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.qyx7slpkd {
  stop-color: var(--svg-color--2ab8e6, #2ab8e6);
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.toy1_lbnc {
  stop-color: var(--svg-color--29cad2, #29cad2);
}

</style>
