<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="c6bmv3q-h"/><path class="jlotzgbzv"/><path class="hsj_fobob"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:timeline" /></template>
<style>
.c6bmv3q-h {
  d: path("M2.5 12h19");
}

.hsj_fobob {
  d: path("M3 3h8v4.25H3Zm10 13.75h8V21h-8Z");
}

.jlotzgbzv {
  fill: currentColor;
  d: path("M5 12a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm10 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
