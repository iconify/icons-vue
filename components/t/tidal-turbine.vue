<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ykblb2b4x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:tidal-turbine" /></template>
<style>
.ykblb2b4x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.5v6l5.25 3M12 8.5l-5.25 3m5.25-3v13m-5 0h10m-15-5q2.5-2 5 0t5 0t5 0t5 0");
}

</style>
