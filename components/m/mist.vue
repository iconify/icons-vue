<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qrj36ccia"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:mist" /></template>
<style>
.qrj36ccia {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 6.5q2.25-1.5 4.5 0t4.5 0t4.5 0t4.5 0M3 12q2.25-1.5 4.5 0t4.5 0m4.5 0q2.25-1.5 4.5 0M3 17.5q2.25-1.5 4.5 0m4.5 0q2.25-1.5 4.5 0t4.5 0");
}

</style>
