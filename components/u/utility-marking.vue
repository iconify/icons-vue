<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dx8s6jb5m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:utility-marking" /></template>
<style>
.dx8s6jb5m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 10A1.5 1.5 0 0 1 7 8.5h1V5h3v3.5h1a1.5 1.5 0 0 1 1.5 1.5v7.5A1.5 1.5 0 0 1 12 19H7a1.5 1.5 0 0 1-1.5-1.5Zm10-4.5h.01m2.99-1.75h.01M2.5 21.5H7m3 0h4.5m3 0h4");
}

</style>
