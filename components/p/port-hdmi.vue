<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b3trtbr4z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:port-hdmi" /></template>
<style>
.b3trtbr4z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 7.5h15.5a1.75 1.75 0 0 1 1.75 1.75v2.667a1.75 1.75 0 0 1-.35 1.05L19.025 15.8a1.75 1.75 0 0 1-1.4.7H6.375a1.75 1.75 0 0 1-1.4-.7L2.85 12.967a1.75 1.75 0 0 1-.35-1.05V9.25A1.75 1.75 0 0 1 4.25 7.5m2.25 4h11");
}

</style>
