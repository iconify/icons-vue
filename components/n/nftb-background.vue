<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGJ0TkreSP)" class="r4i437pya"/><path class="r9_8p9f9l"/></g><defs><linearGradient id="SVGJ0TkreSP" x1="10.597" x2="17.179" y1="4.715" y2="12.96" gradientUnits="userSpaceOnUse"><stop class="j8zu93bxa"/><stop offset="1" class="a_qxsbc3o"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:nftb-background" /></template>
<style>
.a_qxsbc3o {
  stop-color: var(--svg-color--de04ff, #de04ff);
}

.ft5dv1b6b {
  fill: none;
}

.j8zu93bxa {
  stop-color: var(--svg-color--18d3fd, #18d3fd);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.r9_8p9f9l {
  fill: var(--svg-color--fff, #fff);
  d: path("M16.8 18.933V20H7.2v-1.067zM16.8 4v13.867H7.2V4zm-1.067 1.067H8.267V16.8h7.467z");
}

</style>
