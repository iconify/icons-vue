<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kfo77gber"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:rocket-engine" /></template>
<style>
.kfo77gber {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 3h11M9.75 3h4.5v3l-1 1.5c0 3.5 2.25 6 4.75 7.5H6c2.5-1.5 4.75-4 4.75-7.5l-1-1.5ZM12 18v3.25M8.75 18L8 20.25M15.25 18l.75 2.25");
}

</style>
