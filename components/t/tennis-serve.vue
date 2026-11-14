<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mtaf6mbsv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:tennis-serve" /></template>
<style>
.mtaf6mbsv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 8.5a4.5 6 0 1 0 9 0a4.5 6 0 1 0-9 0m4.5 6v7M15 5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0M9 2.5v12m-4.5-6h9");
}

</style>
