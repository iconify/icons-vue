<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hrat12bzv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:tooth-molar" /></template>
<style>
.hrat12bzv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 3h12a2 2 0 0 1 2 2v4c0 2.5-1.5 4-2.5 6l-1 5c-.25 1.25-1.75 1.25-2 0l-1-4.5c-.25-1-2.75-1-3 0l-1 4.5c-.25 1.25-1.75 1.25-2 0l-1-5C5.5 13 4 11.5 4 9V5a2 2 0 0 1 2-2m3.5 0v3m5-3v3");
}

</style>
