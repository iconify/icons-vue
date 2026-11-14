<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fg7u9bcsq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:mesh-node-add" /></template>
<style>
.fg7u9bcsq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0M2 16a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0m14-6.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0M9.75 7.25l-4 6.5m7.5-7.5l3 2M6.75 15l9.5-4.5M18 15v6m-3-3h6");
}

</style>
