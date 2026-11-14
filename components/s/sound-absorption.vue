<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ouv1sib3x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:sound-absorption" /></template>
<style>
.ouv1sib3x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M15.5 3h2A3.5 3.5 0 0 1 21 6.5v11a3.5 3.5 0 0 1-3.5 3.5h-2a3.5 3.5 0 0 1-3.5-3.5v-11A3.5 3.5 0 0 1 15.5 3M15 7h.01M18 12h.01M15 17h.01M3 7c2.5 2.5 2.5 7.5 0 10m4.25-8c1.5 1.5 1.5 4.5 0 6");
}

</style>
