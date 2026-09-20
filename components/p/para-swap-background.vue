<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="fs7765ble"/><path class="uywnjpbas"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:para-swap-background" /></template>
<style>
.fs7765ble {
  fill: var(--svg-color--2669f5, #2669f5);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.uywnjpbas {
  fill: var(--svg-color--fff, #fff);
  d: path("M20 18.399L12.6 5.6L5.2 18.4zM7.4 11.6l3.4-5.999H4zm9.578 5.105H8.222L12.6 9.134z");
}

</style>
