<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="g24xgw49r"/><path class="uq-tsabhi"/><path class="obsp_cbop"/><path class="vayp8ebbs"/><path class="arig0ebmb"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:media-background" /></template>
<style>
.arig0ebmb {
  fill: var(--svg-color--fff, #fff);
  d: path("M6.667 17.297L4.105 14.7l2.561-2.595l.001.001zm0-5.405v.002L4.104 9.298l2.562-2.595zM4 19.999v-5.19l2.562 2.594zm0-5.404V9.403L6.562 12zm0-5.403v-5.19l2.562 2.595z");
}

.ft5dv1b6b {
  fill: none;
}

.g24xgw49r {
  fill: var(--svg-color--92278f, #92278f);
  d: path("M24 0H0v24h24z");
}

.obsp_cbop {
  fill: var(--svg-color--fff, #fff);
  d: path("m17.333 11.894l-2.561-2.595l2.56-2.596zm-.089.106l.002.003l-2.562 2.595l-2.562-2.595l.001-.003zm-5.12 0l2.56-2.6l2.563 2.6zm-.125 5.297v-5.19l2.562 2.594z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.uq-tsabhi {
  fill: var(--svg-color--fff, #fff);
  d: path("m20 9.192l-2.562-2.595L19.998 4zm-.002 5.402l-.001.001l-2.561-2.597l2.56-2.595l.002.001zm0 5.405l-2.562-2.596l2.56-2.595zm-2.665-2.703l-.002-5.19l.002-.001l2.562 2.596zm0-5.402l-.002-5.19L19.896 9.3zm-.001 5.403l-2.562-2.596l2.561-2.593v5.188z");
}

.vayp8ebbs {
  fill: var(--svg-color--fff, #fff);
  d: path("M12 17.297L9.437 14.7L12 12.106zM11.911 12l.001.003l-2.562 2.595l-2.56-2.595V12zM6.79 12l2.543-2.6L11.91 12zm-.123 5.297v-5.19l2.561 2.595zm0-5.405V6.703l2.561 2.595z");
}

</style>
