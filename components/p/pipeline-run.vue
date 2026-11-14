<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="k2q427bcm"/><path class="pbxb4l6gf"/><path class="m5f1-lbyg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pipeline-run" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k2q427bcm {
  d: path("M5.75 5H3.5A1.5 1.5 0 0 0 2 6.5v3A1.5 1.5 0 0 0 3.5 11h2.25m3.5-6h2.5m-2.5 6h2.5m3.5-6h5.25A1.5 1.5 0 0 1 22 6.5v3a1.5 1.5 0 0 1-1.5 1.5h-5.25");
}

.m5f1-lbyg {
  d: path("m17.211 15.691l1.836.988a1.5 1.5 0 0 1 0 2.642l-1.836.988A1.5 1.5 0 0 1 15 18.989v-1.978a1.5 1.5 0 0 1 2.211-1.32");
}

.pbxb4l6gf {
  fill: currentColor;
  d: path("M7.5 3za.75.75 0 0 1 .75.75v8.5a.75.75 0 0 1-.75.75a.75.75 0 0 1-.75-.75v-8.5A.75.75 0 0 1 7.5 3m6 0za.75.75 0 0 1 .75.75v8.5a.75.75 0 0 1-.75.75a.75.75 0 0 1-.75-.75v-8.5A.75.75 0 0 1 13.5 3");
}

</style>
