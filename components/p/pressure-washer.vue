<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hbb-uxb9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:pressure-washer" /></template>
<style>
.hbb-uxb9i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.75 4.75h-3Q3.5 4.75 3.5 6v2q0 1.25.75 1.25t.84 1.25l.32 4.25Q5.5 16 6.75 16h.75q1.25 0 1.16-1.25l-.32-4.25q-.09-1.25.29-1.25Q9 9.25 9 8V6q0-1.25-1.25-1.25M9 7h7.25m-9 9v1.75a2.5 2.5 0 0 0 2.5 2.5h7.5m1.5-15L21 3.5M19 7h2.25m-2.5 1.75L21 10.5");
}

</style>
