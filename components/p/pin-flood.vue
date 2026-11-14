<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vkkwew_kt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pin-flood" /></template>
<style>
.vkkwew_kt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 7c1.75-2.25 4.25-2.25 6 0s4.25 2.25 6 0s4.25-2.25 6 0M3 13c1.75-2.25 4.25-2.25 6 0s4.25 2.25 6 0s4.25-2.25 6 0M3 19c1.75-2.25 4.25-2.25 6 0s4.25 2.25 6 0s4.25-2.25 6 0");
}

</style>
