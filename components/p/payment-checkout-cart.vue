<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="od2uvqb2v"/><path class="yt2ytpejg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:payment-checkout-cart" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.od2uvqb2v {
  d: path("M7.887 7h10.431a1.75 1.75 0 0 1 1.709 2.13l-.222 1a1.75 1.75 0 0 1-1.709 1.37H8.981a1.75 1.75 0 0 1-1.493-.837L6.625 9.25A1.479 1.479 0 0 1 7.887 7");
}

.yt2ytpejg {
  d: path("M2.5 3.5h2L7 15h8m-8 4a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m6.5 0a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0");
}

</style>
