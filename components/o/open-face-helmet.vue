<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w-0nhib4o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:open-face-helmet" /></template>
<style>
.w-0nhib4o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 17.5C3 10 7 3 13.5 3c5 0 8 3.5 8 7.5H15v7Zm10.5 0c0 2.5 2 4 4.5 3");
}

</style>
