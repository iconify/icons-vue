<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wfmmy2slk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:review-diff-stats" /></template>
<style>
.wfmmy2slk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.25 4.5v7M2.75 8h7m-7 9h7M15 5.75h4.5a1.75 1.75 0 0 1 1.75 1.75v1a1.75 1.75 0 0 1-1.75 1.75H15a1.75 1.75 0 0 1-1.75-1.75v-1A1.75 1.75 0 0 1 15 5.75m0 9h1a1.75 1.75 0 0 1 1.75 1.75v1A1.75 1.75 0 0 1 16 19.25h-1a1.75 1.75 0 0 1-1.75-1.75v-1A1.75 1.75 0 0 1 15 14.75");
}

</style>
