<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sy6ukjqhp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:treasury-hedging" /></template>
<style>
.sy6ukjqhp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 7.5h14M14.5 4L18 7.5L14.5 11m-2.3 5.5H6M9.5 13L6 16.5L9.5 20m5.25-1.75a3.25 3.25 0 0 1 6.5 0Zm3.25 0v2a1 1 0 0 1-2 0");
}

</style>
