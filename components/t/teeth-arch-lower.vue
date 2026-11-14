<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d3fkhzbos"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:teeth-arch-lower" /></template>
<style>
.d3fkhzbos {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 7c0 8 4 12 9.5 12s9.5-4 9.5-12A2.75 2.75 0 0 0 16 7c0 3.5-1.5 6.25-4 6.25S8 10.5 8 7a2.75 2.75 0 0 0-5.5 0Zm5.75 2.5l-5 2.75m7 .5l-2 5.5m7.5-8.75l5 2.75m-7 .5l2 5.5");
}

</style>
