<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l4-22pbrt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:robot-vacuum-cleaning" /></template>
<style>
.l4-22pbrt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.25 8h5.5a3.75 3.75 0 0 1 3.75 3.75a3.75 3.75 0 0 1-3.75 3.75h-5.5a3.75 3.75 0 0 1-3.75-3.75A3.75 3.75 0 0 1 12.25 8M13 8V5h4.5v3M5.708 13.725a9.5 9.5 0 0 1 0-3.95m-2.935 4.574a12.5 12.5 0 0 1 0-5.198M2.5 18.5h19");
}

</style>
