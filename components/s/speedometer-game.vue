<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vfyblcb3r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:speedometer-game" /></template>
<style>
.vfyblcb3r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 16.5a9 9 0 0 1 18 0Zm2.75-6.25L7.5 12M12 7.5V10m0 6.5l4.5-4.5M12 16.5h.01");
}

</style>
