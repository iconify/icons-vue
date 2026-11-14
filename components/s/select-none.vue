<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="if8hibcem"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:select-none" /></template>
<style>
.if8hibcem {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 7V5.5a2 2 0 0 1 2-2H7m10 0h1.5a2 2 0 0 1 2 2V7m0 10v1.5a2 2 0 0 1-2 2H17m-10 0H5.5a2 2 0 0 1-2-2V17m7-13.5h3m-3 17h3m-10-10v3m17-3v3m-11-4l5 5m0-5l-5 5");
}

</style>
