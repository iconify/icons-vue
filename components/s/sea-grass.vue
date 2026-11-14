<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rg7o_csxo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:sea-grass" /></template>
<style>
.rg7o_csxo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 21h17m-13 0c-2-5 2-9-.5-14m5 14c-2-5.5 2-10-.5-16.5m5 16.5c-2-5 2-9-.5-13.5M17.5 4a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0");
}

</style>
