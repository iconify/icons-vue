<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i4z5akbbj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:road-debris" /></template>
<style>
.i4z5akbbj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3 21.5l5.5-19m12.5 19l-5.5-19M12 3v4M8.5 17.25v-1.025a1.75 1.75 0 0 1 .513-1.238l1.35-1.35a1.75 1.75 0 0 1 1.525-.489l1.233.205a1.75 1.75 0 0 1 1.278.944l.916 1.833a1.75 1.75 0 0 1 .185.783v.837A1.25 1.25 0 0 1 14.25 19h-4a1.75 1.75 0 0 1-1.75-1.75");
}

</style>
