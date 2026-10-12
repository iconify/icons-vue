<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j-101yb1g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:pilcrow" /></template>
<style>
.j-101yb1g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.5 3.75H13a4.25 4.25 0 0 1 0 8.5h-1.5Zm0 0v16.5M6.75 3.75v16.5m0-16.5h4.75");
}

</style>
