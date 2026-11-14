<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u75wcsbsj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:try-catch" /></template>
<style>
.u75wcsbsj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 14.5v7m3-.5h7l6.5-4.25a1.75 1.75 0 0 0-2.25-2.25L13.5 17h-4m2.75-8a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0ZM5 2.75q4 0 5.5 2.25");
}

</style>
