<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j9vntjbur"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:risk-exposure" /></template>
<style>
.j9vntjbur {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 9a2.25 2.25 0 0 1 0-4.5a6 6 0 0 1 8.5 0A2.25 2.25 0 0 1 16 9ZM8 20v-5l4-3.5l4 3.5v5M3 20h18M4.75 11.5L4 15m15.5-3.5l-.75 3.5");
}

</style>
