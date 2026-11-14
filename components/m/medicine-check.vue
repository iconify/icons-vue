<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="drks4bwzu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:medicine-check" /></template>
<style>
.drks4bwzu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 4h16a1.5 1.5 0 0 1 1.5 1.5v4A1.5 1.5 0 0 1 20 11H4a1.5 1.5 0 0 1-1.5-1.5v-4A1.5 1.5 0 0 1 4 4Zm8 0v7m2.75 7l2 2L21 15.75");
}

</style>
