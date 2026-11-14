<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="venlic9yp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:resource-pool" /></template>
<style>
.venlic9yp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 8a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0M2.5 20.5c0-4 2.5-6 6-6s6 2 6 6M14.75 7a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0M16 13.25c3.5 0 5.5 2.25 5.5 6.25");
}

</style>
