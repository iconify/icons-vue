<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="l31vi2b9a"/><path class="x3i7b_1-b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:reveal" /></template>
<style>
.l31vi2b9a {
  d: path("M2.5 14.5C4.5 11 8 9 12 9s7.5 2 9.5 5.5C19.5 18 16 20 12 20s-7.5-2-9.5-5.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x3i7b_1-b {
  d: path("M9.25 14.5a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0ZM12 2.5v3M5.5 4L7 6.5M18.5 4L17 6.5");
}

</style>
