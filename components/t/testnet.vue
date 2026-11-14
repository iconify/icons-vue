<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nuvoe-ifu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:testnet" /></template>
<style>
.nuvoe-ifu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 9h7M10 9v3.5l-5.25 6.75A1.5 1.5 0 0 0 6 21.5h12a1.5 1.5 0 0 0 1.25-2.25L14 12.5V9m-.75-4.5a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0ZM8 5a1.25 1.25 0 1 0 2.5 0A1.25 1.25 0 1 0 8 5Z");
}

</style>
