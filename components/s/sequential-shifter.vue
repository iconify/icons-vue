<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="upj6h__ag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:sequential-shifter" /></template>
<style>
.upj6h__ag {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 5.5a3 3 0 1 0 6 0a3 3 0 1 0-6 0m3 3V18m-3.5 3.5L6 18h4l1.5 3.5m2.5-15L16.5 4L19 6.5M16.5 4v16M14 17.5l2.5 2.5l2.5-2.5");
}

</style>
