<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i0v1j9b2h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:swimmer-freestyle" /></template>
<style>
.i0v1j9b2h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 11.5a3 3 0 1 0 6 0a3 3 0 1 0-6 0m8.75 3.75C12.5 7 16.5 4.5 19.5 6.5c1.5 1 2 3.5 1.5 6.5M2.5 18.5c3.5-1.75 6.5-1.75 10 0q5.25 2.625 9 0");
}

</style>
