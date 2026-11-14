<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ilvkvkbha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:negative-thought" /></template>
<style>
.ilvkvkbha {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 9.5a8.5 6.5 0 1 0 17 0a8.5 6.5 0 1 0-17 0m.5 9a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m-2 2.75h.01M9.5 9.5h7");
}

</style>
