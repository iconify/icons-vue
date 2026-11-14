<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s2iqetbyf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:plant-ladder" /></template>
<style>
.s2iqetbyf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.066 15.5h3.868a1.75 1.75 0 0 1 1.726 2.038l-.416 2.5A1.75 1.75 0 0 1 8.518 21.5H5.482a1.75 1.75 0 0 1-1.726-1.462l-.416-2.5A1.75 1.75 0 0 1 5.066 15.5m8.934 6v-19m6 0v19M14 7h6m-6 5h6m-6 5h6M7 15.5V12c-.25-2.5-1.75-4-4-4c0 2.25 1.5 4 4 4c.25-2.75 1.75-4.5 4-4.5C11 10 9.5 12 7 12");
}

</style>
