<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nvgxt10nr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:promo-exit-intent" /></template>
<style>
.nvgxt10nr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 6.5V3H3.5v18H12v-7.5M7.5 9.75h12M17 7.25l2.5 2.5l-2.5 2.5m-.5 3h1.379a1.5 1.5 0 0 1 1.06.439l1.75 1.75a1.5 1.5 0 0 1 0 2.122l-1.75 1.75a1.5 1.5 0 0 1-1.06.439H16.5a1.5 1.5 0 0 1-1.5-1.5v-3.5a1.5 1.5 0 0 1 1.5-1.5");
}

</style>
