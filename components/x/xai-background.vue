<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="x_xyf6b3l"/><path clip-rule="evenodd" class="sh39zacpd"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:xai-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.sh39zacpd {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M15.26 16.192H8.74l2.323-4.026l-1.58-2.735L4 18.928h16L12 5.072l-1.58 2.736z");
}

.x_xyf6b3l {
  fill: var(--svg-color--ff253a, #ff253a);
  d: path("M24 0H0v24h24z");
}

</style>
