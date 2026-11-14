<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r7mcqxboh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:shape-intersect" /></template>
<style>
.r7mcqxboh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.75 9h2.5A1.75 1.75 0 0 1 15 10.75v2.5A1.75 1.75 0 0 1 13.25 15h-2.5A1.75 1.75 0 0 1 9 13.25v-2.5A1.75 1.75 0 0 1 10.75 9m-4 6H5.5A2.5 2.5 0 0 1 3 12.5v-1.25m0-3.5V5.5A2.5 2.5 0 0 1 5.5 3h2.25m3.5 0h1.25A2.5 2.5 0 0 1 15 5.5v1.25M17.25 9h1.25a2.5 2.5 0 0 1 2.5 2.5v1.25m0 3.5v2.25a2.5 2.5 0 0 1-2.5 2.5h-2.25m-3.5 0H11.5A2.5 2.5 0 0 1 9 18.5v-1.25");
}

</style>
