<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c3kjpdqza"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:text-outline" /></template>
<style>
.c3kjpdqza {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 2.75h14.5q1 0 1 1v2.5q0 1-1 1h-4q-1 0-1 1v8q0 1-1 1h-2.5q-1 0-1-1v-8q0-1-1-1h-4q-1 0-1-1v-2.5q0-1 1-1m2 2.25h10.5M12 5v10m-5.25 5.75h10.5");
}

</style>
