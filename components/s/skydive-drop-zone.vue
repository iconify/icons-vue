<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w32n7zb4f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:skydive-drop-zone" /></template>
<style>
.w32n7zb4f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 7.5a5 5 0 0 1 10 0Zm0 0l5 5m5-5l-5 5m-9.5 6a9.5 3 0 1 0 19 0a9.5 3 0 1 0-19 0m9.5 0h.01");
}

</style>
