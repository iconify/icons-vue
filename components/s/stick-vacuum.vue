<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nxmu0abbt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:stick-vacuum" /></template>
<style>
.nxmu0abbt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 18.5h7a1.5 1.5 0 0 1 1.5 1.5a1.5 1.5 0 0 1-1.5 1.5H5A1.5 1.5 0 0 1 3.5 20A1.5 1.5 0 0 1 5 18.5m3.5 0l3.25-5.25m3.472-5.506za2.25 2.25 0 0 1 .716 3.1l-1.06 1.696a2.25 2.25 0 0 1-3.1.716a2.25 2.25 0 0 1-.716-3.1l1.06-1.696a2.25 2.25 0 0 1 3.1-.716m2.603-4.364za2.25 2.25 0 0 1 .716 3.1l-.265.424a2.25 2.25 0 0 1-3.101.716a2.25 2.25 0 0 1-.716-3.1l.265-.424a2.25 2.25 0 0 1 3.101-.716");
}

</style>
