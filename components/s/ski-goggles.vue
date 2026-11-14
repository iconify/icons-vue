<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ys98ncjfc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:ski-goggles" /></template>
<style>
.ys98ncjfc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 8.5h16a1.5 1.5 0 0 1 1.5 1.5v4c0 2-1.5 3-3.5 3h-2.5l-2-2.5h-3l-2 2.5H6c-2 0-3.5-1-3.5-3v-4A1.5 1.5 0 0 1 4 8.5m11.5 3H18");
}

</style>
