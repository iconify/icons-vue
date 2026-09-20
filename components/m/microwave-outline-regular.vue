<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="tsdj6se1t"/><path class="f7t8ttbtm"/><path class="fuekpycbr"/><path class="yxq2k2bjb"/><path class="rec8abb_c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:microwave-outline-regular" /></template>
<style>
.f7t8ttbtm {
  d: path("M6 8h9v9H6Z");
}

.fuekpycbr {
  d: path("M17 9a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rec8abb_c {
  d: path("M16.5 16h3");
}

.tsdj6se1t {
  d: path("M3 7a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v11a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

.yxq2k2bjb {
  d: path("M16.5 13h3");
}

</style>
