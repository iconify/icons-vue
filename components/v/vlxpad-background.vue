<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVG2lhJF8Jp)" class="r4i437pya"/><path class="nowal8hph"/><path class="js_pucb-l"/><path class="vj33bzegz"/></g><defs><linearGradient id="SVG2lhJF8Jp" x1="6.496" x2="20" y1="10.098" y2="10.098" gradientUnits="userSpaceOnUse"><stop class="o419w2mdk"/><stop offset="1" class="iiscboqnu"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:vlxpad-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.iiscboqnu {
  stop-color: var(--svg-color--02cbc5, #02cbc5);
}

.js_pucb-l {
  fill: var(--svg-color--fff, #fff);
  d: path("M20 6.666h-9.334l1.111 2.222h4l-.444.889h-3.334l.89 2.222h3.555z");
}

.nowal8hph {
  fill: var(--svg-color--fff, #fff);
  d: path("M6.431 6.666H4l4.445 7.556l3.333-5.334l-1.111-2.222l-2.044 3.644z");
}

.o419w2mdk {
  stop-color: var(--svg-color--0753f7, #0753f7);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.vj33bzegz {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.89 12.001L12 9.78l-2.889 5.11q.628 1.19 1.111 2.445S11.917 13.868 12.89 12");
}

</style>
