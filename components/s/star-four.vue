<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hm54gsb0w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:star-four" /></template>
<style>
.hm54gsb0w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m13.237 6.513l1 2.433a1.5 1.5 0 0 0 .817.817l2.433 1a1.338 1.338 0 0 1 0 2.474l-2.433 1a1.5 1.5 0 0 0-.817.817l-1 2.433a1.338 1.338 0 0 1-2.474 0l-1-2.433a1.5 1.5 0 0 0-.817-.817l-2.433-1a1.338 1.338 0 0 1 0-2.474l2.433-1a1.5 1.5 0 0 0 .817-.817l1-2.433a1.338 1.338 0 0 1 2.474 0");
}

</style>
