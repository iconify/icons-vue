<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u60mwj2av"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:wrestling-singlet" /></template>
<style>
.u60mwj2av {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 2.5H10q2 3 4 0h2.5l.5 6c1.5 1.5 1.5 4 1 6.5q-3 3-4.5 6h-3Q9 18 6 15c-.5-2.5-.5-5 1-6.5Zm-.5 6h10");
}

</style>
