<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u6t78s1hr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:signal-booster" /></template>
<style>
.u6t78s1hr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 21v-6m4.5 6V10M13 21v-2.3m0-2.4V4m5 17v-6m-2.5 2.5L18 15l2.5 2.5");
}

</style>
