<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="feb0_jixg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:ocean-swell" /></template>
<style>
.feb0_jixg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 7Q7.25 4 12 7t9.5 0m-19 5q4.75-3 9.5 0t9.5 0m-19 5q4.75-3 9.5 0t9.5 0");
}

</style>
