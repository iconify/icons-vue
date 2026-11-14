<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="k2q427bcm"/><path class="jrg5ctb-h"/><path class="mp962dbqn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pipeline-error" /></template>
<style>
.jrg5ctb-h {
  fill: currentColor;
  d: path("M6.75 3h1.5v10h-1.5Zm6.3 10h-.3V3h1.5v8.8");
}

.k2q427bcm {
  d: path("M5.75 5H3.5A1.5 1.5 0 0 0 2 6.5v3A1.5 1.5 0 0 0 3.5 11h2.25m3.5-6h2.5m-2.5 6h2.5m3.5-6h5.25A1.5 1.5 0 0 1 22 6.5v3a1.5 1.5 0 0 1-1.5 1.5h-5.25");
}

.mp962dbqn {
  d: path("m15 15l6 6m0-6l-6 6");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
