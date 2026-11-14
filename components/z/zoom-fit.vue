<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n_joelwbt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:zoom-fit" /></template>
<style>
.n_joelwbt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.125 8.5h1.75a2.625 2.625 0 0 1 2.625 2.625v1.75a2.625 2.625 0 0 1-2.625 2.625h-1.75A2.625 2.625 0 0 1 8.5 12.875v-1.75A2.625 2.625 0 0 1 11.125 8.5M2.5 7V2.5H7m-4.5 0L6 6m11-3.5h4.5V7m0-4.5L18 6M2.5 17v4.5H7m-4.5 0L6 18m11 3.5h4.5V17m0 4.5L18 18");
}

</style>
