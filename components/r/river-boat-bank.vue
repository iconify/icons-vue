<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pou46i3lo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:river-boat-bank" /></template>
<style>
.pou46i3lo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 12.75h12l-2.5 3H5Zm6 0V3c3.5.5 5.5 4 5.5 7.25H8.5M21.5 9H19l-3.5 10.25m-13 0q2.25-1.5 4.5 0t4.5 0q2-1.5 4 0");
}

</style>
