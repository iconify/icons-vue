<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gm9hrpbqb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pin-ice-cream" /></template>
<style>
.gm9hrpbqb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 11h12l-6 10.5Zm0 0a3 3 0 0 1 1.25-4.25a5 5 0 0 1 9.5 0A3 3 0 0 1 18 11");
}

</style>
