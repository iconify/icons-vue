<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gskh-cc0p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:sand-grains" /></template>
<style>
.gskh-cc0p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.75 6.5a2.25 1.75 0 1 0 4.5 0a2.25 1.75 0 1 0-4.5 0m-3.5 6a2.25 1.75 0 1 0 4.5 0a2.25 1.75 0 1 0-4.5 0m7 0a2.25 1.75 0 1 0 4.5 0a2.25 1.75 0 1 0-4.5 0m-10.5 6a2.25 1.75 0 1 0 4.5 0a2.25 1.75 0 1 0-4.5 0m7 0a2.25 1.75 0 1 0 4.5 0a2.25 1.75 0 1 0-4.5 0m7 0a2.25 1.75 0 1 0 4.5 0a2.25 1.75 0 1 0-4.5 0");
}

</style>
