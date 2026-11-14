<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n3wo_9boy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:minister" /></template>
<style>
.n3wo_9boy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.472 20.5H4c-.6 0-1-.4-1-1c0-3.25 3.25-5.5 7.5-5.5c1.002 0 1.948.125 2.809.359M6.5 7a4 4 0 1 0 8 0a4 4 0 1 0-8 0m9.5 9.25h4A1.75 1.75 0 0 1 21.75 18v1.75A1.75 1.75 0 0 1 20 21.5h-4a1.75 1.75 0 0 1-1.75-1.75V18A1.75 1.75 0 0 1 16 16.25m.75 0v-1.5h2.5v1.5");
}

</style>
