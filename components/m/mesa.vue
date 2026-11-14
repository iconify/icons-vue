<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q42vsrbkk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:mesa" /></template>
<style>
.q42vsrbkk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 18.5c2 0 3-1 3.5-3l1.5-10H13l1.25 8l1-2.5h3.25l1 4.5c.5 2 1 3 2 3M7 9.5h6.5");
}

</style>
