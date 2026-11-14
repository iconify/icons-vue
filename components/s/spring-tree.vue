<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g2c6z2b2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:spring-tree" /></template>
<style>
.g2c6z2b2m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 21.5v-15m0 8.5L6.5 9.5M12 12l5.5-5.5M3.75 8a1.25 2.25 0 1 0 2.5 0a1.25 2.25 0 1 0-2.5 0m14-3a1.25 2.25 0 1 0 2.5 0a1.25 2.25 0 1 0-2.5 0m-7-.75a1.25 2.25 0 1 0 2.5 0a1.25 2.25 0 1 0-2.5 0");
}

</style>
