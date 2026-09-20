<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="bq3r_miaz"/><path class="f1etaqbet"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:still-life-outline-bold" /></template>
<style>
.bq3r_miaz {
  d: path("M3 20v-7c0 -2 2.5 -3 2.5 -5V4h4v4c0 2 2.5 3 2.5 5v7Z");
}

.f1etaqbet {
  d: path("M15 17a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
