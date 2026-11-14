<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f227uxb6s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:noise-complaint" /></template>
<style>
.f227uxb6s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 8.5h4l5-5v17l-5-5h-4Zm11.828.672a4 4 0 0 1 .931 4.196m1.062-7.113q.438.367.814.796q.377.43.685.911q.307.481.538 1.004q.231.522.381 1.073M14.25 21.5l3.75-7l3.75 7ZM18 17.75v1.75");
}

</style>
