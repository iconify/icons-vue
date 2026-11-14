<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="m8414vq_j"/><path class="ktm3ucc3p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:shoe-polish" /></template>
<style>
.ktm3ucc3p {
  d: path("M4 14v4a8 2.25 0 0 0 16 0v-4M2.75 9.085l12.124-7l1.25 2.165L4 11.25Z");
}

.m8414vq_j {
  d: path("M4 14a8 2.25 0 1 0 16 0a8 2.25 0 1 0-16 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
