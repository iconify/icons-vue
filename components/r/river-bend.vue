<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qjufsxr3y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:river-bend" /></template>
<style>
.qjufsxr3y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 2.5c0 7.5 8 11.5 8 19m2-19c0 7.5 8 11.5 8 19M10.5 12q.75-.75 1.5 0t1.5 0");
}

</style>
