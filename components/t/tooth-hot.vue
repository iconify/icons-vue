<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rq3x0obgs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:tooth-hot" /></template>
<style>
.rq3x0obgs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 9c1.75 0 2.5.75 4 .75S14.25 9 16 9c2 0 3 1.5 3 3.5s-1 3-1.5 4.5l-.5 3.25c-.25 1.25-2 1.25-2.25 0l-.75-2.5c-.25-.75-3.75-.75-4 0l-.75 2.5c-.25 1.25-2 1.25-2.25 0L6.5 17C6 15.5 5 14.5 5 12.5S6 9 8 9m.5-2.75q-1.25-1 0-2t0-2m3.5 4q-1.25-1 0-2t0-2m3.5 4q-1.25-1 0-2t0-2");
}

</style>
