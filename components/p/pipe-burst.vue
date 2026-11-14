<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pmfcgvuba"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pipe-burst" /></template>
<style>
.pmfcgvuba {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 12.5h7l1.25 2l-1.25 2l1.25 2H2.5m19-6h-8l1.25 2l-1.25 2l1.25 2h6.75m-9.5-9v-6m-3.5 6L6.5 5m9 4.5l2-4.5");
}

</style>
