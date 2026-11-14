<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mxp8u1w3i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:self-checkout-help" /></template>
<style>
.mxp8u1w3i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 12.5H13v9H2.5Zm1-8.5L10 3l1.5 7l-7 .75ZM13 14.5h5.5m0 0v-10m-1.5-2h3V5h-3Zm-12.5 13H11m4.25-12.75l-1.5-.5m1.5 3.25l-1.5.75m7.75.25l.25.5");
}

</style>
