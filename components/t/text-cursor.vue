<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jlj7a6hhu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:text-cursor" /></template>
<style>
.jlj7a6hhu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.75 3.75C10.5 3.75 12 4.5 12 6v12c0 1.5-1.5 2.25-3.25 2.25m6.5-16.5C13.5 3.75 12 4.5 12 6v12c0 1.5 1.5 2.25 3.25 2.25M9.5 12h5");
}

</style>
