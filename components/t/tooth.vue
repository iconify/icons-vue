<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="llxhkvbsj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:tooth" /></template>
<style>
.llxhkvbsj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 3.5C5 3.5 4 5.5 4 8s1 4 1.5 6.5l1 5c.25 1.25 1.75 1.25 2 0l1-4.5c.25-1 1.25-1.5 2.5-1.5s2.25.5 2.5 1.5l1 4.5c.25 1.25 1.75 1.25 2 0l1-5C19 12 20 10.5 20 8s-1-4.5-3.5-4.5c-2 0-3 1-4.5 1s-2.5-1-4.5-1Z");
}

</style>
