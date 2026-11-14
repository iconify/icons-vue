<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jw1jpccfi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pin-jewellery" /></template>
<style>
.jw1jpccfi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 15a6 6 0 1 0 12 0a6 6 0 1 0-12 0M9.103 4.496l.46-.768A1.5 1.5 0 0 1 10.849 3h2.302a1.5 1.5 0 0 1 1.286.728l.46.768a1.5 1.5 0 0 1-.225 1.832l-1.611 1.611a1.5 1.5 0 0 1-2.122 0L9.328 6.328a1.5 1.5 0 0 1-.225-1.832M8.5 5.5h7");
}

</style>
