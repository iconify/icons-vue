<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bk18mbb0y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:season-summer" /></template>
<style>
.bk18mbb0y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 8a2 2 0 1 0 4 0a2 2 0 1 0-4 0m2-4.25v-1.5m-3.25 2.5L7.5 3.5m7.75 1.25L16.5 3.5M7.5 8H6m10.5 0H18M2.5 13.75h19M4 17q2-1 4 0t4 0t4 0t4 0M7 20.75q2-1 4 0t4 0t4 0");
}

</style>
