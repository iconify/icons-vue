<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="b-j-eqbzb"/><path class="wgymdbcrb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:tap-to-play" /></template>
<style>
.b-j-eqbzb {
  d: path("M4.5 2.5L20 12L4.5 21.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wgymdbcrb {
  d: path("M8 12a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

</style>
