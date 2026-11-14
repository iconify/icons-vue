<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nlm8v5b1y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:sprouts-tray-kitchen" /></template>
<style>
.nlm8v5b1y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 14h19L20 20H4Zm3 0v-4m0 0c0-2 1.25-3 2.75-3c0 2-1.25 3-2.75 3m5.5 4V8m0 0c0-2 1.25-3 2.75-3c0 2-1.25 3-2.75 3m5.5 6v-4m0 0c0-2 1.25-3 2.75-3c0 2-1.25 3-2.75 3");
}

</style>
