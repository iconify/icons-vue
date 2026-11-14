<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ts36eusbi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:sun-dog" /></template>
<style>
.ts36eusbi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 6.5a8.5 8.5 0 0 1 13 0m0 11a8.5 8.5 0 0 1-13 0m3-5.5a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0Zm-5 0h.01m16.99 0h.01");
}

</style>
