<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xlq1gjbrd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:tennis-club" /></template>
<style>
.xlq1gjbrd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 9a5 7 0 1 0 10 0a5 7 0 1 0-10 0m.05 4.95za1.25 1.25 0 0 1 0 1.768l-3.535 3.535a1.25 1.25 0 0 1-1.768 0a1.25 1.25 0 0 1 0-1.768l3.535-3.535a1.25 1.25 0 0 1 1.768 0m9.9-9.9l-9.9 9.9m1.414-8.486l7.072 7.072M16 18.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0");
}

</style>
