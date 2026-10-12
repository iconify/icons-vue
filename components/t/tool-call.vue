<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l89podbyl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:tool-call" /></template>
<style>
.l89podbyl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M17.39 3.97a5.08 5.08 0 0 0-6.57 6.94l-6.8 6.8a1.6 1.6 0 0 0 2.27 2.27l6.8-6.8a5.08 5.08 0 0 0 6.94-6.57l-3.34 3.35l-2.65-2.65ZM6.25 2.75q.42 3.08 3.5 3.5q-3.08.42-3.5 3.5q-.42-3.08-3.5-3.5q3.08-.42 3.5-3.5");
}

</style>
