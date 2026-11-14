<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dgr0tb0lz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pin-dam" /></template>
<style>
.dgr0tb0lz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.75 4.5h.537a1.75 1.75 0 0 1 1.639 1.136l4.687 12.5a1.75 1.75 0 0 1-1.638 2.364H11.75A1.75 1.75 0 0 1 10 18.75V6.25a1.75 1.75 0 0 1 1.75-1.75m-9.25 16h19M2.5 9Q3.75 8 5 9t2.25 0M2.5 13q1.25-1 2.5 0t2.25 0m6.25-8.5q6.5 0 8 7.5");
}

</style>
