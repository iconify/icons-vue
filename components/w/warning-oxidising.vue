<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oxfuozxcw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:warning-oxidising" /></template>
<style>
.oxfuozxcw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 11c-1-3 .5-5 3-8C11 5.5 12 6.5 13 7.5c.5-1 1-2 1-3c2 2 3.25 4 2.5 6.5a7 7 0 0 0-9 0Zm.25 5.5a4.25 4.25 0 1 0 8.5 0a4.25 4.25 0 1 0-8.5 0Z");
}

</style>
