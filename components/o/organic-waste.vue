<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c83fh6boc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:organic-waste" /></template>
<style>
.c83fh6boc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.75 7c2.75 1 5.75 1 8.5 0c.5 3-1.75 4.5-1.75 7s2.25 4 1.75 7c-2.75-1-5.75-1-8.5 0c-.5-3 1.75-4.5 1.75-7s-2.25-4-1.75-7m4.25.75l.75-4.25m1.75 2.25C15 4 16.25 3 18.5 3c-.5 1.75-1.75 2.75-4 2.75");
}

</style>
