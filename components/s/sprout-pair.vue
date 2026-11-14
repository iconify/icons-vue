<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i3dy98b1u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:sprout-pair" /></template>
<style>
.i3dy98b1u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 20.5V10m0 0c0-4-2.5-6.5-7.5-6.5c0 4 3 6.5 7.5 6.5m0 0c0-4 2.5-6.5 7.5-6.5c0 4-3 6.5-7.5 6.5");
}

</style>
