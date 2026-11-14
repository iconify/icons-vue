<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="nofw6la6m"/><path class="gfjiv5boi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:segmented-mirror" /></template>
<style>
.gfjiv5boi {
  d: path("m12 3.25l4.25 2.5v5L12 13.25l-4.25-2.5v-5Z");
}

.nofw6la6m {
  d: path("m7.75 10.75l4.25 2.5v5l-4.25 2.5l-4.25-2.5v-5Zm8.5 0l4.25 2.5v5l-4.25 2.5l-4.25-2.5v-5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
