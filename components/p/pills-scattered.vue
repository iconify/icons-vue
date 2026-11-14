<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n11-psb6g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pills-scattered" /></template>
<style>
.n11-psb6g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 7a3.75 3.75 0 1 0 7.5 0A3.75 3.75 0 1 0 3 7m10.5 0A3.75 3.75 0 1 0 21 7a3.75 3.75 0 1 0-7.5 0M6 17a6 3.5 0 1 0 12 0a6 3.5 0 1 0-12 0m5.094-3.381l1.812 6.762");
}

</style>
