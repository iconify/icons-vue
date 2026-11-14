<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gr6w8dbql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:soil-sensor" /></template>
<style>
.gr6w8dbql {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 3h8v5H8Zm2 5v12m4-12v12M3 11.5h4m10 0h4M5.5 16h.01m12.99 0h.01M5.5 20h.01m12.99 0h.01");
}

</style>
