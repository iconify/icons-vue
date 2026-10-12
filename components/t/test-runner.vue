<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m80u4obii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:test-runner" /></template>
<style>
.m80u4obii {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.75 3.75H7a2 2 0 0 0-2 2V9.5c0 1.25-.75 2.5-2.25 2.5C4.25 12 5 13.25 5 14.5v3.75a2 2 0 0 0 2 2h.75m8.5-16.5H17a2 2 0 0 1 2 2V9.5c0 1.25.75 2.5 2.25 2.5c-1.5 0-2.25 1.25-2.25 2.5v3.75a2 2 0 0 1-2 2h-.75m-7.5-8L11 14.5l4.25-4.5");
}

</style>
