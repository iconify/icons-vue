<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ng3_azbep"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:north" /></template>
<style>
.ng3_azbep {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12.36 3.41l4.28 7.93q.36.66-.39.66h-8.5q-.75 0-.39-.66l4.28-7.93q.36-.66.72 0M9 21.25V15l6 6.25V15");
}

</style>
