<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ewtslg13t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pin-computer" /></template>
<style>
.ewtslg13t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M14.4 14.5H2.5V3h18v9.2m-9 2.3v5m-2.25 0h4.4M19 22l-2.25-2.75a2.75 2.75 0 1 1 4.5 0Z");
}

</style>
