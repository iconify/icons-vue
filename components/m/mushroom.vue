<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pvwey-dgz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:mushroom" /></template>
<style>
.pvwey-dgz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 12c0-5 4-8 8.5-8s8.5 3 8.5 8Zm6 0v7c0 1 1 1.5 2.5 1.5s2.5-.5 2.5-1.5v-7");
}

</style>
