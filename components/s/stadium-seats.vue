<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yprt34zhq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:stadium-seats" /></template>
<style>
.yprt34zhq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 4h4.5v9h-4.5ZM10 4h4.5v9H10Zm7.25 0h4.5v9h-4.5ZM2.5 16h19M5 16v5m14.5-5v5");
}

</style>
