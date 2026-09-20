<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ymp2b4b6u"/><path class="nlzvizopl"/><path class="n4fl2qbbh"/><path class="mg_lwq87g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:patch-window-outline-bold" /></template>
<style>
.mg_lwq87g {
  d: path("M10.5 11h3");
}

.n4fl2qbbh {
  d: path("M13.5 8H16v6h-2.5");
}

.nlzvizopl {
  d: path("M10.5 8H8v6h2.5");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.ymp2b4b6u {
  d: path("M15 5h5v8l-8 8 -8 -8V5h5");
}

</style>
