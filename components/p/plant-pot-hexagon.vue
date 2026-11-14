<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g6rmfpbxo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:plant-pot-hexagon" /></template>
<style>
.g6rmfpbxo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 11h11l3 5.25l-3 5.25h-11l-3-5.25Zm5.5 0V8c-.25-3-2.25-5-5.25-5C6.75 6 9 8 12 8c.25-3.25 2.25-5.5 5.25-5.5c0 3-2 5.5-5.25 5.5");
}

</style>
