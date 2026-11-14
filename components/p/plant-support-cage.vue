<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sc4s7fw5l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:plant-support-cage" /></template>
<style>
.sc4s7fw5l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m4 7l3.5 14.5M20 7l-3.5 14.5M4.75 10h14.5m-13 6.5h11.5m-5.75 5V6m0 0c0-2 2-3.5 4.5-3.5c0 2-2 3.5-4.5 3.5Z");
}

</style>
