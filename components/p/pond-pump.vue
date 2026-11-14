<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wrd-rbqgo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pond-pump" /></template>
<style>
.wrd-rbqgo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 13H11a4 4 0 0 1 4 4a4 4 0 0 1-4 4H6.5a4 4 0 0 1-4-4a4 4 0 0 1 4-4m2.25 0V9c0-3.75 2.5-6 5.75-6s5 2.5 5 6m0 3c1.25 1.5 1.75 2.5 1.75 3.5a1.75 1.75 0 0 1-3.5 0c0-1 .5-2 1.75-3.5");
}

</style>
