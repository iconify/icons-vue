<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wnq4c_b-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pcr-machine" /></template>
<style>
.wnq4c_b-w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 12h18v9.5H3Zm.5-2.25L17.5 4l1 2.25l-14 5.25Zm4 5.5h.01m4.49 0h.01m4.49 0h.01M7.5 18.5h.01m4.49 0h.01m4.49 0h.01");
}

</style>
