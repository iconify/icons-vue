<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ve8-5vk3v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:person-curly-hair" /></template>
<style>
.ve8-5vk3v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 10.25a2 2 0 0 1-.5-3.75A2.5 2.5 0 0 1 12 4a2.5 2.5 0 0 1 4.5 2.5a2 2 0 0 1-.5 3.75a4 4 0 0 1-8 0M4.5 21.5c0-2.75 3.25-4.5 7.5-4.5s7.5 1.75 7.5 4.5");
}

</style>
