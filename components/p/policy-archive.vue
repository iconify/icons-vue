<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ol90m4b0i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:policy-archive" /></template>
<style>
.ol90m4b0i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 4h13A2.5 2.5 0 0 1 21 6.5A2.5 2.5 0 0 1 18.5 9h-13A2.5 2.5 0 0 1 3 6.5A2.5 2.5 0 0 1 5.5 4m-1 5v9a2 2 0 0 0 2 2h11a2 2 0 0 0 2-2V9M10 13h4");
}

</style>
