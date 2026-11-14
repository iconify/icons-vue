<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="szpzvngrc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:shelf-label-missing" /></template>
<style>
.szpzvngrc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 2.5h19V7h-19Zm3 8.5v-1A1.5 1.5 0 0 1 7 8.5h1.5m7 0H17a1.5 1.5 0 0 1 1.5 1.5v1m0 5.5V18a1.5 1.5 0 0 1-1.5 1.5h-1.5m-7 0H7A1.5 1.5 0 0 1 5.5 18v-1.5m5.5-8h2m-2 11h2M5.5 13v1.5m13-1.5v1.5");
}

</style>
