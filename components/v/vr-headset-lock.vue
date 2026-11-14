<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cy1on7k3r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:vr-headset-lock" /></template>
<style>
.cy1on7k3r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 3.5h9A2.5 2.5 0 0 1 19 6v3.5a2.5 2.5 0 0 1-2.5 2.5h-2a2.5 2.5 0 0 0-5 0h-2A2.5 2.5 0 0 1 5 9.5V6a2.5 2.5 0 0 1 2.5-2.5m-5 4.25H5m14 0h2.5m-4.75 9.75h2.5A1.75 1.75 0 0 1 21 19.25v.5a1.75 1.75 0 0 1-1.75 1.75h-2.5A1.75 1.75 0 0 1 15 19.75v-.5a1.75 1.75 0 0 1 1.75-1.75m-.25 0v-1a1.5 1.5 0 0 1 3 0v1");
}

</style>
