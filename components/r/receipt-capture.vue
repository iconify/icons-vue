<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tspe4ob3b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:receipt-capture" /></template>
<style>
.tspe4ob3b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 7.5V5A2.5 2.5 0 0 1 5 2.5h2.5m9 0H19A2.5 2.5 0 0 1 21.5 5v2.5m0 9V19a2.5 2.5 0 0 1-2.5 2.5h-2.5m-9 0H5A2.5 2.5 0 0 1 2.5 19v-2.5m5-11h9v13l-2.25-1.25L12 18.5l-2.25-1.25L7.5 18.5Zm2.75 4.5h3.5");
}

</style>
