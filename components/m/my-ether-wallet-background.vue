<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="d_1zblewq"/><path class="r94co0b6q"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:my-ether-wallet-background" /></template>
<style>
.d_1zblewq {
  fill: var(--svg-color--1896a4, #1896a4);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r94co0b6q {
  fill: var(--svg-color--fff, #fff);
  d: path("M4 12a8 8 0 1 0 16 0a8 8 0 0 0-16 0m8 5.027c-2.704 0-5.023-2.192-5.023-4.897c0-.635.121-1.368.34-1.924l2.16.919q-.012.046-.026.114a2.7 2.7 0 0 0-.117.78l.002.03a2.65 2.65 0 0 0 3.255 2.548l1.226 2.083a4.9 4.9 0 0 1-1.815.347m4.633-3.038l-5.477-2.32l3.513-.016c-.126-1.274-1.436-2.309-2.67-2.309c-.281 0-.56.046-.824.138L9.96 7.416A4.9 4.9 0 0 1 12 6.973c2.704 0 5.015 2.233 5.015 4.937c0 .729-.094 1.458-.38 2.08");
}

</style>
