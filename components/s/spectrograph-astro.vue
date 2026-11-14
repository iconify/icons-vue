<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k46pyvbjx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:spectrograph-astro" /></template>
<style>
.k46pyvbjx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12.587 8.419l3.758 8.094A1.75 1.75 0 0 1 14.758 19H7.242a1.75 1.75 0 0 1-1.587-2.487l3.758-8.094a1.75 1.75 0 0 1 3.174 0M2.5 14l5.25-2m6.5 0l7.25-3.5M14.25 12l7.25.5m-7.25-.5l7.25 4.5");
}

</style>
