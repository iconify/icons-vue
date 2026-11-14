<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z-vgf809b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:night-reading" /></template>
<style>
.z-vgf809b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 13c-2-1.5-5.5-2-9.5-1.5V20c4-.5 7.5 0 9.5 1.5c2-1.5 5.5-2 9.5-1.5v-8.5c-4-.5-7.5 0-9.5 1.5m0 0v8.5m3-19a3.5 3.5 0 1 0 0 6a3.5 3.5 0 0 1 0-6");
}

</style>
