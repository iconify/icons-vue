<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nk5p8zc0p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:table-delete-row" /></template>
<style>
.nk5p8zc0p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 3h9A3.5 3.5 0 0 1 20 6.5V9a3.5 3.5 0 0 1-3.5 3.5h-9A3.5 3.5 0 0 1 4 9V6.5A3.5 3.5 0 0 1 7.5 3M4 7.75h16M9 18.5h6");
}

</style>
