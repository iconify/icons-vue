<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="btrj6jbvt"/><path class="heggqxl8x"/><path class="w1h0b2rfq"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:pivx-background" /></template>
<style>
.btrj6jbvt {
  fill: var(--svg-color--5e4778, #5e4778);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.heggqxl8x {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.8 5.6H6.4V4h6.4a4.8 4.8 0 0 1 0 9.6H8V20H6.4v-8h6.4a3.2 3.2 0 1 0 0-6.4");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.w1h0b2rfq {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.733 9.332H6.4v-1.6h5.333z");
}

</style>
