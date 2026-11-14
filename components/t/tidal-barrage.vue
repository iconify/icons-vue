<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="heif7oohg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:tidal-barrage" /></template>
<style>
.heif7oohg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 13V5h19v8h-3v-3a1.5 1.5 0 0 0-3 0v3h-2v-3a1.5 1.5 0 0 0-3 0v3h-2v-3a1.5 1.5 0 0 0-3 0v3Zm0 4.5q2.25-2 4.5 0t4.5 0t4.5 0t4.5 0");
}

</style>
