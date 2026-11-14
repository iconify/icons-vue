<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="v0pn7vbww"/><path class="z9x8te4hu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:photo-caption" /></template>
<style>
.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v0pn7vbww {
  d: path("M3.5 2.5h17v12h-17Z");
}

.z9x8te4hu {
  d: path("m7 11.5l3.25-3.25l3.25 3.25m3-5h.01M3.5 18h17m-17 3.5H14");
}

</style>
