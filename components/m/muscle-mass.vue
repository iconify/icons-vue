<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dppva43se"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:muscle-mass" /></template>
<style>
.dppva43se {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 13.5c1-6 7-7.5 9.75-3.5L14 7.5a3 3 0 1 1 5.25-.5l.75 7c.5 4-2 6-5 6H3M14 7.5l5.25-.5");
}

</style>
