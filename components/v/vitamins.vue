<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ci1v9ib9s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:vitamins" /></template>
<style>
.ci1v9ib9s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M14.8 13.8a3.25 3.25 0 0 0-4.6-4.6l-6.5 6.5a3.25 3.25 0 0 0 4.6 4.6Zm-7.85-1.35l4.6 4.6M18 2.75q.39 2.86 3.25 3.25q-2.86.39-3.25 3.25q-.39-2.86-3.25-3.25q2.86-.39 3.25-3.25");
}

</style>
