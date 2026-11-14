<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="dh2jzoboc"/><path class="ghqeqtqiw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:turn-right-ahead" /></template>
<style>
.dh2jzoboc {
  d: path("m12 2l10 10l-10 10L2 12Z");
}

.ghqeqtqiw {
  d: path("M9.5 15.5v-4a2 2 0 0 1 2-2h4m-2.25-2.25L15.5 9.5l-2.25 2.25");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
