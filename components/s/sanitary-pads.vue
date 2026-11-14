<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h_c_58bmg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:sanitary-pads" /></template>
<style>
.h_c_58bmg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 2.5h4a2 2 0 0 1 2 2v15a2 2 0 0 1-2 2h-4a2 2 0 0 1-2-2v-15a2 2 0 0 1 2-2ZM8 9l-3.5 1a1 1 0 0 0-1 1v2a1 1 0 0 0 1 1L8 15m8-6l3.5 1a1 1 0 0 1 1 1v2a1 1 0 0 1-1 1L16 15m-4-6.5v7");
}

</style>
