<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u0z5bbxud"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:path-brick" /></template>
<style>
.u0z5bbxud {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.658 19.526l5-15A1.5 1.5 0 0 1 10.081 3.5h3.838a1.5 1.5 0 0 1 1.423 1.026l5 15a1.5 1.5 0 0 1-1.423 1.974H5.081a1.5 1.5 0 0 1-1.423-1.974M5 15.5h14m-12-6h10m-5 12v-6m-2.5 0v-6m5 6v-6m-2.5 0v-6");
}

</style>
