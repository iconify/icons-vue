<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="t_3k31h_x"/><path class="yji_subkq"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:ngc-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.t_3k31h_x {
  fill: var(--svg-color--ec1b2e, #ec1b2e);
  d: path("M24 0H0v24h24z");
}

.yji_subkq {
  fill: var(--svg-color--fff, #fff);
  d: path("m15.2 12.626l-2.112.172l1.8-4.727l-5.5.772l-.587 5.234l1.316-.075L9.877 20zM9.388 8.41l5.43-.68l-2.56-1.108S12.589 4.676 10.72 4l-.224.66s1.212.24 1.04 2.011z");
}

</style>
