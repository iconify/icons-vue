<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kajfomvdj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:smooth-legs" /></template>
<style>
.kajfomvdj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 2.5h12v6H4Zm6 6l-2 13m-1.5-16h7m4.5 8q0 4 4 4q-4 0-4 4q0-4-4-4q4 0 4-4Z");
}

</style>
