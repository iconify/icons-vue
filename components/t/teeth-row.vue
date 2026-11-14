<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yl1pmtoax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:teeth-row" /></template>
<style>
.yl1pmtoax {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 7.5h17a1 1 0 0 1 1 1v7a1 1 0 0 1-1 1h-17a1 1 0 0 1-1-1v-7a1 1 0 0 1 1-1Zm4.25 0v9m4.25-9v9m4.25-9v9");
}

</style>
