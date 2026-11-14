<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rn6sbubux"/><path class="bsyu8jmin"/><path class="kfwqxi4eo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:season-cycle" /></template>
<style>
.bsyu8jmin {
  d: path("M3 17.25L4 15l2.25 1M4.013 9.093a8.5 8.5 0 0 1 15.974 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kfwqxi4eo {
  d: path("M21 6.75L20 9l-2.25-1M9 15c0-4.5 2.5-6 6-6q0 6-6 6m1.25-1.25l2.5-2.5");
}

.rn6sbubux {
  d: path("M19.987 14.907a8.5 8.5 0 0 1-15.974 0");
}

</style>
