<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wiwrjia1b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:room-too-hot" /></template>
<style>
.wiwrjia1b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 13.5v-8a3 3 0 0 1 6 0v8a4.5 4.5 0 1 1-6 0M8 18V7m9.75 7.75c0 1.75-2 2.5-2 4.5a2.75 2.75 0 0 0 5.5 0c0-1.5-.75-2.25-1.25-2.75c-.25.75-.75 1.25-1.5 1.25c.25-1.25-.25-2.25-.75-3");
}

</style>
