<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s2i26czoe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:trail-map-search" /></template>
<style>
.s2i26czoe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m4.4 5.75l3.45-1.5q1.15-.5 2.3-.02l3.7 1.54q1.15.48 2.3-.02l3.45-1.5q1.15-.5 1.15.75v11.5q0 1.25-1.15 1.75l-3.45 1.5q-1.15.5-2.3.02l-3.7-1.54q-1.15-.48-2.3.02l-3.45 1.5q-1.15.5-1.15-.75V7.5q0-1.25 1.15-1.75m1.35 10.5L7 15.5m2-1.25l1.25-.5m2-.75l1-.75m1.5-1.25l.75-1m1-2.75l2.5 2.5m0-2.5l-2.5 2.5");
}

</style>
