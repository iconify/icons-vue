<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nm6jn0b5q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:zen-stones" /></template>
<style>
.nm6jn0b5q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.25 18c0-3 1.6-5.25 3.75-5.25S15.75 15 15.75 18Zm1-9.25c0-1 1.25-1.5 2.75-1.5s2.75.5 2.75 1.5s-1.25 1.5-2.75 1.5s-2.75-.5-2.75-1.5M2.75 18h18.5m-15.5 0a6.5 6.5 0 0 1 .5-2.5m-3 2.5a9 9 0 0 1 .7-3.5m13.8 1a6.5 6.5 0 0 1 .5 2.5m1.8-3.5a9 9 0 0 1 .7 3.5m-18 2.75c1.55-.6 3.1-.6 4.63 0s3.08.6 4.62 0s3.08-.6 4.62 0s3.08.6 4.63 0");
}

</style>
