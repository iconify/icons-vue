<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r19o_ybea"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:most-read" /></template>
<style>
.r19o_ybea {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 4h18M3 9.5h18M3 15h7m7.5-2l1 2.5l2.5.25l-1.75 1.75l.75 2.75l-2.5-1.5l-2.5 1.5l.75-2.75L14 15.75l2.5-.25Z");
}

</style>
