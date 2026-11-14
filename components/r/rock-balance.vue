<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="x9bwhdcqu"/><path class="adglo2bwc"/><path class="uu_315b5i"/><path class="r89v_6xdl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:rock-balance" /></template>
<style>
.adglo2bwc {
  d: path("M8 13.25a4 4 0 1 0 8 0a4 4 0 1 0-8 0Z");
}

.r89v_6xdl {
  d: path("M9.5 3.75a2.5 1.5 0 1 0 5 0a2.5 1.5 0 1 0-5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.uu_315b5i {
  d: path("M5 7.25a7 2 0 1 0 14 0a7 2 0 1 0-14 0Z");
}

.x9bwhdcqu {
  d: path("M4.5 19.25a7.5 2 0 1 0 15 0a7.5 2 0 1 0-15 0Z");
}

</style>
