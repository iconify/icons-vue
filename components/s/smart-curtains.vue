<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bkdw_-cro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:smart-curtains" /></template>
<style>
.bkdw_-cro {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 2.5h19V6h-19ZM4 6l-.5 14.5q2-1.75 3.75 0q1.75-1.75 3.5 0L10.5 6M20 6l.5 14.5q-2-1.75-3.75 0q-1.75-1.75-3.5 0L13.5 6");
}

</style>
