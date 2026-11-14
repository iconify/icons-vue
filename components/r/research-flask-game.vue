<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l472nx71j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:research-flask-game" /></template>
<style>
.l472nx71j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 3v6.5L4.75 20q-.5 1 .75 1h13q1.25 0 .75-1L14 9.5V3M8.5 3h7M7 15.5h10m-7 2.75h.01m3.99 0h.01");
}

</style>
