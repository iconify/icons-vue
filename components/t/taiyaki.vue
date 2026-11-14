<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tsav82b4w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:taiyaki" /></template>
<style>
.tsav82b4w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 12c2-4 6.5-5 11-3.5c2 .5 3 1.5 3 3.5s-1 3-3 3.5C9.5 17 5 16 3 12m15.522-1.184l.728-.566a1.394 1.394 0 0 1 2.25 1.1v1.3a1.394 1.394 0 0 1-2.25 1.1l-.728-.566a1.5 1.5 0 0 1 0-2.368M7 11h.01");
}

</style>
