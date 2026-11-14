<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vqac3r68u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:x-ray-crystallography" /></template>
<style>
.vqac3r68u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12.976 6.837l2 1.714A1.5 1.5 0 0 1 15.5 9.69v4.62a1.5 1.5 0 0 1-.524 1.139l-2 1.714a1.5 1.5 0 0 1-1.952 0l-2-1.714A1.5 1.5 0 0 1 8.5 14.31V9.69a1.5 1.5 0 0 1 .524-1.139l2-1.714a1.5 1.5 0 0 1 1.952 0M12 6v12M3.5 3.5L6 6m14.5-2.5L18 6M3.5 20.5L6 18m14.5 2.5L18 18");
}

</style>
