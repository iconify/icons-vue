<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ouxzn8bxg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pruning-shears" /></template>
<style>
.ouxzn8bxg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 14.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm5 5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm-1-5.75l14-5.25m-10.25 9l5.25-14m-2 1L21 12");
}

</style>
