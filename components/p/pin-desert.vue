<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s7wak7-5c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pin-desert" /></template>
<style>
.s7wak7-5c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 20.5v-4H6.5A2.5 2.5 0 0 1 4 14v-4a1.5 1.5 0 0 1 3 0v3.5h3V6a2 2 0 0 1 4 0v5.5h3V8a1.5 1.5 0 0 1 3 0v4a2.5 2.5 0 0 1-2.5 2.5H14v6m-11 0h18");
}

</style>
