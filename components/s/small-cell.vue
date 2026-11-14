<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="btea0_s-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:small-cell" /></template>
<style>
.btea0_s-c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.25 5h1.5a1.75 1.75 0 0 1 1.75 1.75v3.5A1.75 1.75 0 0 1 12.75 12h-1.5a1.75 1.75 0 0 1-1.75-1.75v-3.5A1.75 1.75 0 0 1 11.25 5m.75 7v9.5M6.75 6q-1.5 2.5 0 5M4 4q-2.5 4.5 0 9m13.25-7q1.5 2.5 0 5M20 4q2.5 4.5 0 9");
}

</style>
