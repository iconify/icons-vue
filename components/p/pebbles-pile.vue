<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ndwoz2bnu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pebbles-pile" /></template>
<style>
.ndwoz2bnu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 16.5a4.25 3 0 1 0 8.5 0a4.25 3 0 1 0-8.5 0m11.5.25a3.75 2.75 0 1 0 7.5 0a3.75 2.75 0 1 0-7.5 0M7.5 8.5a4.75 3.25 0 1 0 9.5 0a4.75 3.25 0 1 0-9.5 0");
}

</style>
