<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="px9yqbhtz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:wine-aerator" /></template>
<style>
.px9yqbhtz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 3h10l-3.75 4v1.5h-2.5V7Zm0 8.25h10q0 6.25-5 6.25t-5-6.25Zm5 6.25v3.75m-3 0h6");
}

</style>
