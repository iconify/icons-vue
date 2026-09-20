<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="fyqcx5b2p"/><path class="beet91bdv"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:zec-background" /></template>
<style>
.beet91bdv {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.28 14.947h4.93v2.948h-2.947V20h-2.528v-2.105H7.79v-2.676l4.907-6.166H7.79V6.105h2.945V4h2.528v2.105h2.948v2.676z");
}

.ft5dv1b6b {
  fill: none;
}

.fyqcx5b2p {
  fill: var(--svg-color--ecb244, #ecb244);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
