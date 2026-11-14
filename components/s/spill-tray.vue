<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ik9walbjh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:spill-tray" /></template>
<style>
.ik9walbjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 14h2l1 5.5h13l1-5.5h2M12 2.5S8.5 6.75 8.5 9a3.5 3.5 0 0 0 7 0c0-2.25-3.5-6.5-3.5-6.5");
}

</style>
