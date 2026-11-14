<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uvkd9rbvn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:trampoline" /></template>
<style>
.uvkd9rbvn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 12a9.5 3.5 0 1 0 19 0a9.5 3.5 0 1 0-19 0Zm2 2.25V19M9 15.25v5.25m6-5.25v5.25m4.5-6.25V19M8.5 5.5q3.5-4 7 0");
}

</style>
