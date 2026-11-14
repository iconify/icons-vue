<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ihq6j-bnq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:sanitary-pads" /></template>
<style>
.ihq6j-bnq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.5za4 4 0 0 1 4 4v11a4 4 0 0 1-4 4a4 4 0 0 1-4-4v-11a4 4 0 0 1 4-4M8 9l-3.5 1a1 1 0 0 0-1 1v2a1 1 0 0 0 1 1L8 15m8-6l3.5 1a1 1 0 0 1 1 1v2a1 1 0 0 1-1 1L16 15m-4-6.5v7");
}

</style>
