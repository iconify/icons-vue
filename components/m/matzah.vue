<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oyss9dayu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:matzah" /></template>
<style>
.oyss9dayu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 4q4-1 8 0t8 0q1 4 0 8t0 8q-4-1-8 0t-8 0q-1-4 0-8t0-8m3.5 5.5H9m2.25 0h1.5m2.25 0h1.5m-9 5H9m2.25 0h1.5m2.25 0h1.5");
}

</style>
