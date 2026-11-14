<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ftsl330xz"/><path class="zgh193bfs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:team-flag" /></template>
<style>
.ftsl330xz {
  d: path("M5 2.5v19M5 3c4-1.25 7 3 14.5.5V13C12 15.5 9 11.25 5 13");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zgh193bfs {
  d: path("M10.25 9a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

</style>
