<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t2u45abnb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:rubber-duck" /></template>
<style>
.t2u45abnb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3 9l3.5 2.5h4C9 10 9 5 13.5 4c3-.5 4.5 1.5 4.5 3.5h3c0 1.5-1 2.25-2.75 2.5C20 11.5 20.5 13 20 14.5c-1 1.5-3 2-8 2H8C4.5 16.5 3 14 3 9Zm11.75-2.25h.01M3 20.5q2.75-1.75 5.5 0t5.5 0t5.5 0");
}

</style>
