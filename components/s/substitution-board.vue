<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ugpso53iv"/><path class="tjth2nzla"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:substitution-board" /></template>
<style>
.tjth2nzla {
  d: path("M5.5 6.25h3.75l-2 6.5m7.5-5.25l2-1.25v6.5");
}

.ugpso53iv {
  d: path("M2.5 3.5h19v12h-19Zm9.5 12V21m0-17.5v12");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
