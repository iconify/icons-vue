<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cd8tgubdf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:ping-pong-bounce" /></template>
<style>
.cd8tgubdf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M15.25 7a3 3 0 1 0 6 0a3 3 0 1 0-6 0M3 5q5.5 2 7 13.5q1.5-7.5 3-8.5M2.5 18.5h19");
}

</style>
