<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rtia53bin"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:tooth-root" /></template>
<style>
.rtia53bin {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 3.25c1.75 0 2.75.75 5 .75s3.25-.75 5-.75c2 0 3.25 1.5 3.25 3.75s-1.25 3.75-2 5.5L17 20c-.15 1-1.5 1.25-2 .25L12.75 15h-1.5L9 20.25c-.5 1-1.85.75-2-.25l-1.25-8c-.75-1.75-2-3.25-2-5.5C3.75 4.75 5 3.25 7 3.25M9.75 8.5l-1 6.75m5.5-6.75l1 6.75");
}

</style>
