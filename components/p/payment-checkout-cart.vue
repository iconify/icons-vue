<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="laf40hbce"/><path class="gex9hhbvr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:payment-checkout-cart" /></template>
<style>
.gex9hhbvr {
  d: path("M2.5 3.5h2L7 15h8m-8 4a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm6.5 0a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Z");
}

.laf40hbce {
  d: path("M5.25 7H20.5l-1 4.5H8Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
