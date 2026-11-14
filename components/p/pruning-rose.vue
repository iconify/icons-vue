<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vf_l_mb2v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pruning-rose" /></template>
<style>
.vf_l_mb2v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 3.5q2.25 2 4-1q1.75 3 4 1V7a4 4 0 0 1-8 0Zm4 7.5v10.5m0-4l2.236-1.118M13.5 16l8 3.5m-5.5-6l3.5 8");
}

</style>
