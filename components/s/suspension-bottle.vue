<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yrnpykb6v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:suspension-bottle" /></template>
<style>
.yrnpykb6v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 5V3.25a.75.75 0 0 1 .75-.75h4.5a.75.75 0 0 1 .75.75V5Zm.5 0Q7 6.5 7 9v10.5A1.5 1.5 0 0 0 8.5 21h7a1.5 1.5 0 0 0 1.5-1.5V9q0-2.5-2.5-4M10 17.5h.01m3.99 0h.01M4 9q-1.5 3 0 6m16-6q1.5 3 0 6");
}

</style>
