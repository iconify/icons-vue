<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="y4a1ohbhq"/><path class="k4bitbb0t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:parking-timer" /></template>
<style>
.k4bitbb0t {
  d: path("M10.25 17.5v-8h2.25a2.25 2.25 0 0 1 0 4.5h-2.25");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y4a1ohbhq {
  d: path("M4 13.5a8 8 0 1 0 16 0a8 8 0 1 0-16 0Zm6-11h4m-2 0v3");
}

</style>
