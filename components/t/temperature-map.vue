<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ngwtpxbzc"/><path class="j92leabef"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:temperature-map" /></template>
<style>
.j92leabef {
  d: path("M18.5 17.25V14.5a1 1 0 0 1 2 0v2.75a2.25 2.25 0 1 1-2 0Z");
}

.ngwtpxbzc {
  d: path("M14.401 19.608L8.5 17.5l-6 2.5V6l6-2.5l7 2.5l6-2.5v7.567M8.5 3.5v14m7-11.5v10.2");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
