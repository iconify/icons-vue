<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h733qhb9l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:spoiler" /></template>
<style>
.h733qhb9l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 17.25V14.5q0-1.25.63-1.87Q4 12 5.25 12h1q1.25 0 1.69-1.17l.62-1.66Q9 8 10.25 8h3.5Q15 8 15.44 9.17l.62 1.66Q16.5 12 17.75 12h1q1.25 0 1.88.63q.62.62.62 1.87v2.75q0 1.25-1.25 1.25H4q-1.25 0-1.25-1.25M2.75 5h18.5M4.5 5v7m15-7v7m-8.75 3.25h2.5m-7.5 0h2m8.5 0h2");
}

</style>
