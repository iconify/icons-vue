<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bmcoufbvk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:nitrogen-molecule" /></template>
<style>
.bmcoufbvk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 17a4.25 4.25 0 1 0 8.5 0a4.25 4.25 0 1 0-8.5 0m10-10a4.25 4.25 0 1 0 8.5 0a4.25 4.25 0 1 0-8.5 0M10 14l4-4");
}

</style>
