<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iy08uob3b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:mood-confused" /></template>
<style>
.iy08uob3b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 14.5a7 7 0 1 0 14 0a7 7 0 1 0-14 0M7 13h.01M12 13h.01M7 18l5-1m4.5-12.5a2.25 2.25 0 1 1 3 2c-.75.5-.75 1-.75 1.75m0 2.75h.01");
}

</style>
