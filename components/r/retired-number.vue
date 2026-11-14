<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="q0fhzzbzo"/><path class="maf2nbr4z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:retired-number" /></template>
<style>
.maf2nbr4z {
  d: path("M9.25 14.5a2.75 3.75 0 1 0 5.5 0a2.75 3.75 0 1 0-5.5 0Zm0 4.25l5.5-8.5");
}

.q0fhzzbzo {
  d: path("m9 3l3 3.5L15 3l5.5 2.5l1 5l-3.5 1V21H6v-9.5l-3.5-1l1-5Zm0 0h6");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
