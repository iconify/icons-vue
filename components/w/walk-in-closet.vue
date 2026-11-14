<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uvm1trb5r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:walk-in-closet" /></template>
<style>
.uvm1trb5r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 3.5h19M3 3.5v18m18-18v18M7 3.5v3m-2.25 4L7 6.5l2.25 4h-4.5m7.25-7V9m-2.25 4L12 9l2.25 4h-4.5M17 3.5v3m-2.25 4l2.25-4l2.25 4h-4.5");
}

</style>
