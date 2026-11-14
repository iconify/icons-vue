<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="daz0_7b2e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:nose" /></template>
<style>
.daz0_7b2e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.5 3c0 5-1.5 8-3.5 10.5c-1.5 2-1 5 1.5 5c1 0 1.75 1 3.5 1s2.5-1 3.5-1c2.5 0 3-3 1.5-5C15 11 13.5 8 13.5 3");
}

</style>
