<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jpnhj1bgl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:root-canal" /></template>
<style>
.jpnhj1bgl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 7c2 0 2.5 1 4 1s2-1 4-1c2.5 0 3.5 1.75 3.5 4.25c0 2.25-1 3.5-1.5 5.25l-.75 3.75c-.25 1.5-2.25 1.5-2.5 0l-1-3c-.25-1-3.25-1-3.5 0l-1 3c-.25 1.5-2.25 1.5-2.5 0L6 16.5c-.5-1.75-1.5-3-1.5-5.25C4.5 8.75 5.5 7 8 7m-.875-5h1.75A1.125 1.125 0 0 1 10 3.125A1.125 1.125 0 0 1 8.875 4.25h-1.75A1.125 1.125 0 0 1 6 3.125A1.125 1.125 0 0 1 7.125 2M8 4.25V18");
}

</style>
