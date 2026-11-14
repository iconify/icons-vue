<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k17r1zlnc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:penalty-signal" /></template>
<style>
.k17r1zlnc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.25 5.5a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0ZM3 21.5V15c0-2.25 2-3.75 5-3.75c1.75 0 2.75.5 3.5 1.25l7 4.75m-7-4.75c1 1 1.5 1.5 1.5 3v6m7.5-.5h.01");
}

</style>
