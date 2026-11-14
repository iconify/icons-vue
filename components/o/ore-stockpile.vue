<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xxbs2itql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:ore-stockpile" /></template>
<style>
.xxbs2itql {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 17.5L7.5 11A2 2 0 0 1 11 9a1.8 1.8 0 0 1 3.5.5A1.8 1.8 0 0 1 17 12l4.25 5.5m-18.75 0h19");
}

</style>
