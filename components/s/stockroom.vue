<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dpuw28bfz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:stockroom" /></template>
<style>
.dpuw28bfz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 2.5v19m18-19v19M3 9h18M3 15.5h18m-18 6h18M5.5 3.5h6V9h-6Zm7.5 2h5.5V9H13Zm-7.5 6h5v4h-5Zm7-1h6v5h-6Zm-5.5 7h10v4H7Z");
}

</style>
