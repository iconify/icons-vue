<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ez3o53c-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:track-lighting" /></template>
<style>
.ez3o53c-p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 7.5h19m-14 0l-1 2.75M5 9.75l2.75 1l-1.25 6l-4.25-1.5Zm7-2.25v3m-1.5 0h3l.75 6h-4.5Zm6-3l1 2.75m1.5-.5l-2.75 1l1.25 6l4.25-1.5Z");
}

</style>
