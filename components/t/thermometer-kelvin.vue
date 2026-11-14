<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fspc6ht8r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:thermometer-kelvin" /></template>
<style>
.fspc6ht8r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 15.5v-10a2.5 2.5 0 0 1 5 0v10a3.5 3.5 0 1 1-5 0Zm9.5-8v10m6.5-10l-6.5 6m2-1.75L20 17.5M6.5 9v9");
}

</style>
