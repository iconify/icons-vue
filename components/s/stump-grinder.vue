<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="j-_-jub7s"/><path class="kh_gvjbww"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:stump-grinder" /></template>
<style>
.j-_-jub7s {
  d: path("M4.5 15.5v4l-1.5 2h15l-1.5-2v-4");
}

.kh_gvjbww {
  d: path("M4.5 15.5a6 2 0 1 0 12 0a6 2 0 1 0-12 0Zm10-9.5l-1.25 1.25v1.5h-1.5L10.5 10L9.25 8.75h-1.5v-1.5L6.5 6l1.25-1.25v-1.5h1.5L10.5 2l1.25 1.25h1.5v1.5Zm-4 0h.01m3.99 0h4l2.5 4");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
