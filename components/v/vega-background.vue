<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="mumfproca"/><path class="qtzagcx7m"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:vega-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.mumfproca {
  fill: var(--svg-color--000, #000);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.qtzagcx7m {
  fill: var(--svg-color--fff, #fff);
  d: path("M5.333 4h2.134v11.733H5.333zM9.6 17.867H7.467v-2.134H9.6zm2.133 0V20H9.6v-2.133zm0 0v-2.134h2.134v2.134zM14.4 4h2.133v9.6H14.4zm2.133 9.6h2.134v2.133h-2.134z");
}

</style>
