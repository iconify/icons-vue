<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gtdhn4b_x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:trash-can-full" /></template>
<style>
.gtdhn4b_x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 10.5L4.75 21h9.5L16 10.5Zm1 0c.5-4 3.5-5 5.5-3.5c1.5-3 5-2 5.5 3.5m6.042-1.409za1.5 1.5 0 0 1 1.217 1.738l-1.563 8.863a1.5 1.5 0 0 1-1.738 1.217a1.5 1.5 0 0 1-1.217-1.738l1.563-8.863a1.5 1.5 0 0 1 1.738-1.217");
}

</style>
