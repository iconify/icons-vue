<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="j8xc2acvj"/><path class="cx52u447e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:temporary-traffic-light" /></template>
<style>
.cx52u447e {
  fill: currentColor;
  d: path("M11 5a1 1 0 1 0 2 0a1 1 0 1 0-2 0Zm0 3.5a1 1 0 1 0 2 0a1 1 0 1 0-2 0Zm0 3.5a1 1 0 1 0 2 0a1 1 0 1 0-2 0Z");
}

.j8xc2acvj {
  d: path("M8 2h8v13H8Zm4 13v3m0 0l-5 3.5m5-3.5l5 3.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
