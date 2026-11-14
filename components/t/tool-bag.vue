<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n_sibcnqa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:tool-bag" /></template>
<style>
.n_sibcnqa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 10h17v9a2 2 0 0 1-2 2h-13a2 2 0 0 1-2-2ZM8 10V7a4 4 0 0 1 8 0v3M3.5 14.5h17");
}

</style>
