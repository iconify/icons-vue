<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="x4-rr57vq"/><path class="ijarvjb3h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:police-badge" /></template>
<style>
.ijarvjb3h {
  d: path("M8.5 11.5a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x4-rr57vq {
  d: path("M7 3c1.5 1 3.5 1 5-.5C13.5 4 15.5 4 17 3l2.5 2.5q-1.125 2.25 0 4.5c0 5-3 9-7.5 11.5C7.5 19 4.5 15 4.5 10q1.125-2.25 0-4.5Z");
}

</style>
