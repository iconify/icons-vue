<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nmc31wbow"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:soccer-kit-hanging" /></template>
<style>
.nmc31wbow {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 8L3 11l1.75 4L7 14v7.5h10V14l2.25 1L21 11l-5.5-3a3.5 3.5 0 0 1-7 0M10 4.75a2 2 0 1 1 2 2V8");
}

</style>
