<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y4fzxmsyg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:traffic-flood" /></template>
<style>
.y4fzxmsyg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 8c2-2.5 4 2.5 6.5 0s4.5 2.5 7 0s4 0 5.5 0m-19 5c2-2.5 4 2.5 6.5 0s4.5 2.5 7 0s4 0 5.5 0m-19 5c2-2.5 4 2.5 6.5 0s4.5 2.5 7 0s4 0 5.5 0");
}

</style>
