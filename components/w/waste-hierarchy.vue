<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="izt3_0bql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:waste-hierarchy" /></template>
<style>
.izt3_0bql {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m4.5 17.25l5.75-9.75m2.902-1.245l5.569 9.854m-.373 3.136l-11.319-.104M7.5 8.75l2.75-1.25l.25 3m8.513 2.603l-.292 3.006l-2.723-1.283m-6.511 6.071l-2.458-1.756l2.473-1.717");
}

</style>
