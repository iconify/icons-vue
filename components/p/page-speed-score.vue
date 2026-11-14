<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hvf1rvi4c"/><path class="o1gpfmb0y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:page-speed-score" /></template>
<style>
.hvf1rvi4c {
  d: path("M3.773 18.75a9.5 9.5 0 1 1 16.454 0");
}

.o1gpfmb0y {
  d: path("m12.75 8.5l-3.25 5H12l-.75 4l3.25-5H12Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
