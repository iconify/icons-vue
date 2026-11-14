<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t28kxvfhk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:sublimation" /></template>
<style>
.t28kxvfhk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.625 13h8.75A2.625 2.625 0 0 1 19 15.625v3.25a2.625 2.625 0 0 1-2.625 2.625h-8.75A2.625 2.625 0 0 1 5 18.875v-3.25A2.625 2.625 0 0 1 7.625 13M8 10.25c-1.5-1.75 1.5-3.75 0-6m4 6c-1.5-1.75 1.5-3.75 0-6m4 6c-1.5-1.75 1.5-3.75 0-6");
}

</style>
