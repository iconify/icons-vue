<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="pvx_7ub7k"/><path class="t1g6ihpfd"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:xki-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.pvx_7ub7k {
  fill: var(--svg-color--2a00ff, #2a00ff);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.t1g6ihpfd {
  fill: var(--svg-color--fff, #fff);
  d: path("M9.42 4H6.322v11.87h3.096v-5.274l4.645 5.275h3.613l-5.16-5.936L17.16 4h-3.613L9.42 9.275zM7.871 20a1.548 1.548 0 1 0 0-3.097a1.548 1.548 0 0 0 0 3.097");
}

</style>
