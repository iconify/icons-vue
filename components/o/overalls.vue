<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j-i45g5sr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:overalls" /></template>
<style>
.j-i45g5sr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 5.75h6q1 0 1 1V10q0 1 1 1h.5q1 0 1.12.99l1.01 8.27q.12.99-.88.99H15q-1 0-1.32-.95l-1.36-4.1q-.32-.95-.64 0l-1.36 4.1q-.32.95-1.32.95H5.25q-1 0-.88-.99l1.01-8.27Q5.5 11 6.5 11H7q1 0 1-1V6.75q0-1 1-1m-.25.75l-2-3.75m8.5 3.75l2-3.75m-7 5.75h3.5");
}

</style>
