<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="eo9i31ggr"/><path class="yu98p6lrm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:suture-needle" /></template>
<style>
.eo9i31ggr {
  d: path("M3.5 12.5c0-5 3.5-8.5 8-8.5s8 3.5 8 8h-2c0-3.5-2.5-6-6-6s-6 3-8 6.5Zm15-3v1");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yu98p6lrm {
  d: path("M18.5 12c0 4-4 3.5-5 6s2 3.75 8 2.75");
}

</style>
