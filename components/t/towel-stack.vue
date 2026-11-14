<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q6uoalbhp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:towel-stack" /></template>
<style>
.q6uoalbhp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.75 16h12.5a2.25 2.25 0 0 1 2.25 2.25a2.25 2.25 0 0 1-2.25 2.25H5.75a2.25 2.25 0 0 1-2.25-2.25A2.25 2.25 0 0 1 5.75 16m1-6.5h10.5a2.25 2.25 0 0 1 2.25 2.25A2.25 2.25 0 0 1 17.25 14H6.75a2.25 2.25 0 0 1-2.25-2.25A2.25 2.25 0 0 1 6.75 9.5m1-6.5h8.5a2.25 2.25 0 0 1 2.25 2.25a2.25 2.25 0 0 1-2.25 2.25h-8.5A2.25 2.25 0 0 1 5.5 5.25A2.25 2.25 0 0 1 7.75 3");
}

</style>
