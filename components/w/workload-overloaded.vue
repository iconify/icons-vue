<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uzd-52b7r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:workload-overloaded" /></template>
<style>
.uzd-52b7r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 13.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm-1.5 8c0-2 1.75-2.75 4-2.75s4 .75 4 2.75m4-6h6v6h-6Zm-1.5-6h6v6h-6Zm-1.5-6h6v6h-6Z");
}

</style>
