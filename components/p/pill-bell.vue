<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mieaa1b8d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pill-bell" /></template>
<style>
.mieaa1b8d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 14.5C5 13 5.5 11 5.5 8a5 5 0 0 1 10 0c0 3 .5 5 2 6.5Zm5 0a2 2 0 0 0 4 0m3.875 3h3.75A1.875 1.875 0 0 1 22 19.375a1.875 1.875 0 0 1-1.875 1.875h-3.75a1.875 1.875 0 0 1-1.875-1.875a1.875 1.875 0 0 1 1.875-1.875");
}

</style>
