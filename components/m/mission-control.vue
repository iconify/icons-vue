<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pdm8bcb9k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:mission-control" /></template>
<style>
.pdm8bcb9k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 5.75H5A1.75 1.75 0 0 1 6.75 7.5v3A1.75 1.75 0 0 1 5 12.25h-.75A1.75 1.75 0 0 1 2.5 10.5v-3a1.75 1.75 0 0 1 1.75-1.75m7-1.5h1.5A1.75 1.75 0 0 1 14.5 6v4.5a1.75 1.75 0 0 1-1.75 1.75h-1.5A1.75 1.75 0 0 1 9.5 10.5V6a1.75 1.75 0 0 1 1.75-1.75M19 5.75h.75A1.75 1.75 0 0 1 21.5 7.5v3a1.75 1.75 0 0 1-1.75 1.75H19a1.75 1.75 0 0 1-1.75-1.75v-3A1.75 1.75 0 0 1 19 5.75m-14.25 9.5h14.5a2.25 2.25 0 0 1 2.25 2.25a2.25 2.25 0 0 1-2.25 2.25H4.75A2.25 2.25 0 0 1 2.5 17.5a2.25 2.25 0 0 1 2.25-2.25m7.25-3v3");
}

</style>
