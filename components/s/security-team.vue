<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ys17i9b7y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:security-team" /></template>
<style>
.ys17i9b7y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 19.5c0-2.8 2.5-4.75 5.5-4.75s5.5 1.95 5.5 4.75c0 .5-.4 1-1 1h-9c-.6 0-1-.5-1-1M9 7.25a3 3 0 1 0 6 0a3 3 0 1 0-6 0M2.5 9a2 2 0 1 0 4 0a2 2 0 1 0-4 0m15 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0M2 17.5c0-1.9 1.2-3 2.5-3.25M22 17.5c0-1.9-1.2-3-2.5-3.25");
}

</style>
