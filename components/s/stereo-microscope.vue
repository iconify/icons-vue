<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ftqmlrq7z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:stereo-microscope" /></template>
<style>
.ftqmlrq7z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 18.5h14a1.5 1.5 0 0 1 1.5 1.5a1.5 1.5 0 0 1-1.5 1.5H5A1.5 1.5 0 0 1 3.5 20A1.5 1.5 0 0 1 5 18.5m9-9h3.5v9M9.25 7h3A1.75 1.75 0 0 1 14 8.75v2a1.75 1.75 0 0 1-1.75 1.75h-3a1.75 1.75 0 0 1-1.75-1.75v-2A1.75 1.75 0 0 1 9.25 7m-.5 0L7 2.75M12.75 7l1.75-4.25");
}

</style>
