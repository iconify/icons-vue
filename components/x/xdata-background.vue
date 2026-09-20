<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="ngtfmnbuq"/><path class="hbbdp7b_y"/><path class="jz_hoxbwx"/><path class="eth0_4b7k"/><path class="ct14f_bns"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:xdata-background" /></template>
<style>
.ct14f_bns {
  fill: var(--svg-color--fff, #fff);
  d: path("M5.29 15.035v1.93C5.29 18.642 8.294 20 12 20s6.71-1.358 6.71-3.035v-1.93h-.026c-.31 1.548-3.185 2.756-6.684 2.756s-6.374-1.208-6.684-2.756z");
}

.eth0_4b7k {
  fill: var(--svg-color--fff, #fff);
  d: path("M5.29 11.727v1.93c0 1.672 3.004 3.035 6.71 3.035s6.71-1.363 6.71-3.035v-1.93h-.026c-.31 1.548-3.185 2.756-6.684 2.756s-6.374-1.213-6.684-2.756z");
}

.ft5dv1b6b {
  fill: none;
}

.hbbdp7b_y {
  fill: var(--svg-color--fff, #fff);
  d: path("M12 10.07c3.706 0 6.71-1.359 6.71-3.035S15.706 4 12 4S5.29 5.359 5.29 7.035S8.294 10.07 12 10.07");
}

.jz_hoxbwx {
  fill: var(--svg-color--fff, #fff);
  d: path("M5.29 8.413v1.93c0 1.677 3.004 3.035 6.71 3.035s6.71-1.358 6.71-3.035V8.418h-.026c-.31 1.543-3.185 2.756-6.684 2.756S5.626 9.96 5.316 8.413z");
}

.ngtfmnbuq {
  fill: var(--svg-color--25ae5f, #25ae5f);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
