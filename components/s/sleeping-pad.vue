<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wb90duroj"/><path class="f_0l5nbmu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:sleeping-pad" /></template>
<style>
.f_0l5nbmu {
  d: path("M2.5 12v3a2 2 0 0 0 2 2h15a2 2 0 0 0 2-2v-3M8.75 7v7m6.5-7v7");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wb90duroj {
  d: path("M2.5 7h19v7h-19Z");
}

</style>
