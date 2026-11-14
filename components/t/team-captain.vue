<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="u54x9_b_z"/><path class="ivqra7frk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:team-captain" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ivqra7frk {
  d: path("m12.367 15.994l.021.056a1.5 1.5 0 0 0 1.347.979l.059.002a.392.392 0 0 1 .227.699l-.046.036a1.5 1.5 0 0 0-.515 1.584l.016.057a.392.392 0 0 1-.594.432l-.049-.033a1.5 1.5 0 0 0-1.666 0l-.049.033a.392.392 0 0 1-.594-.432l.016-.057a1.5 1.5 0 0 0-.515-1.584l-.046-.036a.392.392 0 0 1 .227-.699l.059-.002a1.5 1.5 0 0 0 1.347-.979l.021-.056a.392.392 0 0 1 .734 0M3.75 17.5h2.5");
}

.u54x9_b_z {
  d: path("M8.75 5.75a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0M3.5 21.5v-2c0-4.5 3.75-7.25 8.5-7.25s8.5 2.75 8.5 7.25v2");
}

</style>
