<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jsg7029uw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:toast-info" /></template>
<style>
.jsg7029uw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.75 6h8.5a5.25 5.25 0 0 1 5.25 5.25v1.5A5.25 5.25 0 0 1 16.25 18h-8.5a5.25 5.25 0 0 1-5.25-5.25v-1.5A5.25 5.25 0 0 1 7.75 6m-.5 3.25h.01m-.01 3v2.5M11 12h6.5");
}

</style>
