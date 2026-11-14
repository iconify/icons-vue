<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yspc2kqdl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:tablet-stylus" /></template>
<style>
.yspc2kqdl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.875 2.5h4.25A4.375 4.375 0 0 1 15.5 6.875v10.25a4.375 4.375 0 0 1-4.375 4.375h-4.25A4.375 4.375 0 0 1 2.5 17.125V6.875A4.375 4.375 0 0 1 6.875 2.5M7 18.5h4M19.5 4za1 1 0 0 1 1 1v10.711a1.5 1.5 0 0 1-.107.557L20 17.25a.539.539 0 0 1-1 0l-.393-.982a1.5 1.5 0 0 1-.107-.557V5a1 1 0 0 1 1-1");
}

</style>
