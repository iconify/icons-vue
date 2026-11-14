<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q3hlnybkb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:robot-technician" /></template>
<style>
.q3hlnybkb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.375 4.5h3.75A4.375 4.375 0 0 1 15.5 8.875v2.25a4.375 4.375 0 0 1-4.375 4.375h-3.75A4.375 4.375 0 0 1 3 11.125v-2.25A4.375 4.375 0 0 1 7.375 4.5m1.875-2v2M6.75 10h.01m4.99 0h.01M19 14.5l-1.75 1.75l2.5 2.5L21.5 17m-3 .5l-3.25 3.25");
}

</style>
