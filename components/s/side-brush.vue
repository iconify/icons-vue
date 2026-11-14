<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="j__ejdl6m"/><path class="yvdcteb7g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:side-brush" /></template>
<style>
.j__ejdl6m {
  d: path("M11.25 11a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yvdcteb7g {
  d: path("M13.75 8.5q0-4.5 6.75-5.5M16 12.25q3.75 2.25 1.25 8.5m-5.75-8.5q-3.75 2.25-8-3");
}

</style>
