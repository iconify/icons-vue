<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hqmjuj-ej"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:mushroom-button" /></template>
<style>
.hqmjuj-ej {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 13.5C4 7 8 4 12 4s8 3 8 9.5Zm4.5 0v5A2.5 2.5 0 0 0 11 21h2a2.5 2.5 0 0 0 2.5-2.5v-5");
}

</style>
