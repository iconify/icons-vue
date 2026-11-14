<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="td20ip0rl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:roof-tiles" /></template>
<style>
.td20ip0rl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.747 17.768l6.944-12.425a1.5 1.5 0 0 1 2.618 0l6.944 12.425A1.5 1.5 0 0 1 18.943 20H5.057a1.5 1.5 0 0 1-1.31-2.232M7.5 11h9M5 15.5h14m-7-8V11m-2 0v4.5m4-4.5v4.5m-6 0V20m4-4.5V20m4-4.5V20");
}

</style>
