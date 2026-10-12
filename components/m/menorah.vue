<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d3ppfrb4x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:menorah" /></template>
<style>
.d3ppfrb4x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.75c1 1.1 1.5 1.9 1.5 2.6a1.5 1.5 0 0 1-3 0c0-.7.5-1.5 1.5-2.6M3 13V9.75M5.25 13V9.75M7.5 13V9.75M9.75 13V9.75M12 13V9m2.25 4V9.75M16.5 13V9.75M18.75 13V9.75M21 13V9.75M2.75 13h18.5M12 13v7.25m-4.25 0h8.5");
}

</style>
