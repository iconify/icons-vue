<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uvfuh3b6a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:medicine-check" /></template>
<style>
.uvfuh3b6a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 4h12a3.5 3.5 0 0 1 3.5 3.5A3.5 3.5 0 0 1 18 11H6a3.5 3.5 0 0 1-3.5-3.5A3.5 3.5 0 0 1 6 4m6 0v7m2.75 7l2 2L21 15.75");
}

</style>
