<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m3r_xwbuc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:person-crosswalk" /></template>
<style>
.m3r_xwbuc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.5 4.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0m1.25 4.75L11 13.5M8 17l3-3.5l3 3.5m-5.25-5l3.75-2.25L16 12M3 20.5h3.5m3.75 0h3.5m3.75 0H21");
}

</style>
