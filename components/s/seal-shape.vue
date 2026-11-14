<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a0ho7-kpr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:seal-shape" /></template>
<style>
.a0ho7-kpr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.5 6.5a2.25 2.25 0 1 1 3 0A2.25 2.25 0 1 1 16 8a2.25 2.25 0 1 1 1.5 2.5a2.25 2.25 0 1 1 0 3A2.25 2.25 0 1 1 16 16a2.25 2.25 0 1 1-2.5 1.5a2.25 2.25 0 1 1-3 0A2.25 2.25 0 1 1 8 16a2.25 2.25 0 1 1-1.5-2.5a2.25 2.25 0 1 1 0-3A2.25 2.25 0 1 1 8 8a2.25 2.25 0 1 1 2.5-1.5");
}

</style>
