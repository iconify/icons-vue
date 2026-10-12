<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xwnvahyoh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:roadmap" /></template>
<style>
.xwnvahyoh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 20.25h11a2.75 2.75 0 0 0 0-5.5h-6a2.75 2.75 0 0 1 0-5.5h2m6.75 2.5c-1.5-1.25-3.25-3-3.25-5a3.25 3.25 0 0 1 6.5 0c0 2-1.75 3.75-3.25 5");
}

</style>
