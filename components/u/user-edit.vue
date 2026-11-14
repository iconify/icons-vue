<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s6dka4bck"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:user-edit" /></template>
<style>
.s6dka4bck {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 20c0-2.75 2.9-4.75 6.5-4.75s6.5 2 6.5 4.75c0 .6-.4 1-1 1h-11c-.6 0-1-.4-1-1M5.25 8.25a3.75 3.75 0 1 0 7.5 0a3.75 3.75 0 1 0-7.5 0m10 5.625l.155-.699a1.5 1.5 0 0 1 .404-.735l3.316-3.316a1.237 1.237 0 0 1 1.75 0a1.237 1.237 0 0 1 0 1.75l-3.316 3.316a1.5 1.5 0 0 1-.735.404l-.699.155a.733.733 0 0 1-.875-.875");
}

</style>
