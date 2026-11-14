<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tt7qp0b0f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:mortgage-paid-off" /></template>
<style>
.tt7qp0b0f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m5 14l7-6l7 6v7.5H5ZM3.802 3.789l1.644.598l-.598 1.645l-1.645-.599ZM9 2.75h.01M12.5 4.5c.75-1.5 2 1 3-.5q.75-1.125 1.5-.75m1.503 3.137l1.586-.739l.74 1.586l-1.586.739ZM21 11h.01M3 10.25h.01m3.49-2c.5-1 1.5 0 2.25-1.25");
}

</style>
