<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pawmx-bnv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:skeleton-specimen" /></template>
<style>
.pawmx-bnv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 8C2 8 2 16 5.5 16Zm0 4H19m0 0l2.75-3M19 12l2.75 3M8.25 7.5v9M11 8v8m2.75-7.25v6.5m2.75-5.5v4.5");
}

</style>
