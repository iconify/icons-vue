<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="jbxp8vivr"/><path class="isco9uklj"/><path class="fv6li-lem"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:ramp-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.fv6li-lem {
  fill: var(--svg-color--fff, #fff);
  d: path("M12 4L5.263 8.003v7.994L12 20l6.737-4.003V8.003zm-3.368 9.938v-3.896L12 8.125l3.368 1.917v3.897l-3.393 1.943zm0 2.246v-1.352l4.493 2.634l-1.125.672zm8.42-1.115l-3.177 1.953l-1.164-.696l3.5-1.954V9.608L12 7.264L7.79 9.608v6.018l-.843-.612V8.985L12 5.971l5.053 2.96z");
}

.isco9uklj {
  fill: var(--svg-color--fff, #fff);
  d: path("M14.105 13.294L12 14.583l-2.105-1.29V10.71L12 9.416l2.105 1.294z");
}

.jbxp8vivr {
  fill: var(--svg-color--0d285a, #0d285a);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
