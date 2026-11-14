<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v_9fjebmt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:volunteer-befriending" /></template>
<style>
.v_9fjebmt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 7.5a3.75 3.75 0 1 0 7.5 0a3.75 3.75 0 1 0-7.5 0m-1.75 13c0-4 2.5-6 5.5-6s5.5 2 5.5 6m.75-11a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0m1 6.25c2.5-1.5 6.25-.25 6.25 3.75");
}

</style>
