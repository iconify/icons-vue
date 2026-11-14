<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yy6a6so5e"/><path class="nv4_0pbcb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:news-website" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nv4_0pbcb {
  d: path("M7.5 10H10a1.5 1.5 0 0 1 1.5 1.5V13a1.5 1.5 0 0 1-1.5 1.5H7.5A1.5 1.5 0 0 1 6 13v-1.5A1.5 1.5 0 0 1 7.5 10m6.75.5h3.25M14.25 15h3.25");
}

.yy6a6so5e {
  d: path("M7.75 2.5h8A5.25 5.25 0 0 1 21 7.75v5A5.25 5.25 0 0 1 15.75 18h-8a5.25 5.25 0 0 1-5.25-5.25v-5A5.25 5.25 0 0 1 7.75 2.5M2.5 7H21");
}

</style>
