<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c1lu6rbkq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:ten-key-pad" /></template>
<style>
.c1lu6rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.875 3h8.25A4.375 4.375 0 0 1 20.5 7.375v9.25A4.375 4.375 0 0 1 16.125 21h-8.25A4.375 4.375 0 0 1 3.5 16.625v-9.25A4.375 4.375 0 0 1 7.875 3M7 6.5h.01m3.49 0h.01m3.49 0h.01M7 10h.01m3.49 0h.01M14 10h.01M7 13.5h.01m3.49 0h.01m3.49 0h.01M7 17h3.5m3.5 0h.01m3.24-10.5V10m0 3.5V17");
}

</style>
