<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gk9fekb6h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:piano-pedals" /></template>
<style>
.gk9fekb6h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 3h15v4.5h-15Zm1.75 7.5h2l-1.75 10h-4Zm4.75 0h2l1 10h-4Zm4.75 0h2l3.75 10h-4Z");
}

</style>
