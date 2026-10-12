<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="m-m3cc3aa"/><path class="j0zhp9btl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:post-office-sharp" /></template>
<style>
.j0zhp9btl {
  d: path("M9 11.75h7.25v6.5h-8.5v-6.5zm-.75.75L12 15.25l3.75-2.75");
}

.m-m3cc3aa {
  d: path("m4.27 8.52l6.71-4.79L12 3l1.02.73l6.71 4.79l1.02.73v12H3.25v-12z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
