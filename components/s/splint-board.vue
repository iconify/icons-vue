<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s0ojyrl_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:splint-board" /></template>
<style>
.s0ojyrl_m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.5 2.75h3q2.5 0 2.74 2.49l1.27 13.52q.24 2.49-2.26 2.49h-6.5q-2.5 0-2.26-2.49L7.76 5.24Q8 2.75 10.5 2.75M10 5.5h4m-4.75 12v2m5.5-2v2M4.25 9.25h15.5M4.25 15h15.5");
}

</style>
