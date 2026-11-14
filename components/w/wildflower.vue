<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e95qby-vm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:wildflower" /></template>
<style>
.e95qby-vm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 5.75a2.25 2.25 0 1 1 4 0a2.25 2.25 0 1 1 1.25 3.75A2.25 2.25 0 1 1 12 12a2.25 2.25 0 1 1-3.25-2.5A2.25 2.25 0 1 1 10 5.75M12 12v9.5m0-13h.01m-.01 11c0-2.5 1.75-4 4.25-4c0 2.5-1.75 4-4.25 4");
}

</style>
