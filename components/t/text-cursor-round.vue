<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m0yqracdx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:text-cursor-round" /></template>
<style>
.m0yqracdx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 3a4 4 0 0 1 4 4v10a4 4 0 0 1-4 4m8-18a4 4 0 0 0-4 4v10a4 4 0 0 0 4 4");
}

</style>
