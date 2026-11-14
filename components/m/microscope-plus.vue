<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rxh2w1bpr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:microscope-plus" /></template>
<style>
.rxh2w1bpr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.25 2.5h.5A1.75 1.75 0 0 1 9.5 4.25v5A1.75 1.75 0 0 1 7.75 11h-.5A1.75 1.75 0 0 1 5.5 9.25v-5A1.75 1.75 0 0 1 7.25 2.5M9.5 5c5 0 6.5 6 3 10v1.771M3.5 14h6m-6 4.5h8.7M18 15v6m-3-3h6");
}

</style>
