<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vvizpdb9q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:map-3d" /></template>
<style>
.vvizpdb9q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m6.5 6l3.75-1.5l3.5 1.5l3.75-1.5l4 13.5l-6.25 2.5l-6.5-2.5l-6.25 2.5Zm3.75-1.5L8.75 18m5-12l1.5 14.5");
}

</style>
