<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oasf55boz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:monsoon" /></template>
<style>
.oasf55boz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.22 11.87A2.94 2.94 0 0 1 7.81 6a4.23 4.23 0 0 1 7.85-1.02a3.31 3.31 0 0 1-.44 6.89ZM8.5 14l-.75 2.5m4.5-2.5l-.75 2.5M16 14l-.75 2.5m-12.5 3.75q2.31-2 4.63 0t4.63 0t4.63 0t4.63 0");
}

</style>
