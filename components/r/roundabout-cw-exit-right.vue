<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="e3x6pq0mc"/><path class="xx1tbu30f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:roundabout-cw-exit-right" /></template>
<style>
.e3x6pq0mc {
  d: path("M10 21.5v-5a5.5 5.5 0 1 1 5.5-5.5h5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xx1tbu30f {
  d: path("M18.25 8.75L20.5 11l-2.25 2.25M10 16.5a5.5 5.5 0 0 0 5.5-5.5M8 3.5l2 2l-2 2");
}

</style>
