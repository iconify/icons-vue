<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGrHyzmcjf)" class="r4i437pya"/><path class="g3-890bsd"/></g><defs><linearGradient id="SVGrHyzmcjf" x1="17.012" x2="6.827" y1="5.791" y2="17.835" gradientUnits="userSpaceOnUse"><stop class="fd4p3kd0x"/><stop offset="1" class="tdm9ps87s"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:mvi-background" /></template>
<style>
.fd4p3kd0x {
  stop-color: var(--svg-color--3afce7, #3afce7);
}

.ft5dv1b6b {
  fill: none;
}

.g3-890bsd {
  fill: var(--svg-color--fff, #fff);
  d: path("M16.364 4a1.454 1.454 0 1 0 0 2.909a1.454 1.454 0 0 0 0-2.909M6.075 10.546c0-.665 2.652-1.213 5.925-1.213s5.925.548 5.925 1.213c0 .669-2.968 1.212-5.925 1.212c-2.967 0-5.925-.534-5.925-1.212m-1.833.242s0 1.94 7.758 1.94s7.758-1.94 7.758-1.94c0 1.988-1.833 6.177-2.968 6.894c-.581.369-.751-.28-.93-.984c-.17-.66-.354-1.362-.902-1.328c-.563.039-1.019 1.178-1.475 2.322C13.023 18.846 12.564 20 12 20c-.562 0-1.018-1.164-1.474-2.318c-.465-1.173-.921-2.341-1.493-2.307c-.538.038-.728.727-.892 1.367c-.185.693-.35 1.323-.941.945c-1.12-.717-2.958-4.901-2.958-6.9");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.tdm9ps87s {
  stop-color: var(--svg-color--fc5cdd, #fc5cdd);
}

</style>
