<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w52g9mc9y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:mushroom-ring" /></template>
<style>
.w52g9mc9y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 5.5a2.5 2.5 0 0 1 5 0Zm2.5 0V8m4.25 2.25a2.5 2.5 0 0 1 5 0Zm2.5 0v2.5m-5.25 5.5a2.5 2.5 0 0 1 5 0Zm2.5 0v2.5m-10.5-2.5a2.5 2.5 0 0 1 5 0Zm2.5 0v2.5m-5.25-10.5a2.5 2.5 0 0 1 5 0Zm2.5 0v2.5");
}

</style>
