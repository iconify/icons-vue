<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xvetpcxhc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:rice-paddy" /></template>
<style>
.xvetpcxhc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 14.75v-7m0 3.75C5 10 4 9 2.75 8.75m2.25.5c0-1.75 1-2.75 2.5-3m4.5 8.5v-7m0 3.75C12 10 11 9 9.75 8.75m2.25.5c0-1.75 1-2.75 2.5-3m4.5 8.5v-7m0 3.75c0-1.5-1-2.5-2.25-2.75m2.25.5c0-1.75 1-2.75 2.25-3M2.75 18c1.5 0 1.5-1 3.1-1s1.5 1 3.1 1s1.5-1 3.05-1s1.5 1 3.1 1s1.5-1 3.05-1s1.5 1 3.1 1m-18.5 3.25c1.5 0 1.5-1 3.1-1s1.5 1 3.1 1s1.5-1 3.05-1s1.5 1 3.1 1s1.5-1 3.05-1s1.5 1 3.1 1");
}

</style>
