<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tupalviei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:sort-amount-up" /></template>
<style>
.tupalviei {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 20V4m-3 3l3-3l3 3m4.25-3h1A1.25 1.25 0 0 1 16 5.25a1.25 1.25 0 0 1-1.25 1.25h-1a1.25 1.25 0 0 1-1.25-1.25A1.25 1.25 0 0 1 13.75 4m0 6.75h3.5A1.25 1.25 0 0 1 18.5 12a1.25 1.25 0 0 1-1.25 1.25h-3.5A1.25 1.25 0 0 1 12.5 12a1.25 1.25 0 0 1 1.25-1.25m0 6.75h6A1.25 1.25 0 0 1 21 18.75A1.25 1.25 0 0 1 19.75 20h-6a1.25 1.25 0 0 1-1.25-1.25a1.25 1.25 0 0 1 1.25-1.25");
}

</style>
