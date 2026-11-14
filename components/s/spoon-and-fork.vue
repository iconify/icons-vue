<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zphcc9bva"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:spoon-and-fork" /></template>
<style>
.zphcc9bva {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 3.5V8a2.5 2.5 0 0 0 5 0V3.5m-2.5 7v10m5-13a2.5 4 0 1 0 5 0a2.5 4 0 1 0-5 0Zm2.5 4v9");
}

</style>
