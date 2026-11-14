<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pcgirybcb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:theory" /></template>
<style>
.pcgirybcb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm-7 13a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm14 0a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0ZM10.75 7.25l-4.5 8.5m7-8.5l4.5 8.5M7.5 18h9");
}

</style>
