<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="shu3xdl9q"/><circle class="v90gbqbox"/><circle class="h_tsn8bxt"/><path class="hrlkjybrs"/><path class="k6xbvzbvu"/><path class="bheqf2b1q"/><path class="y8jdc-bgt"/><path class="kgwbfcbts"/><path class="hdj33kbau"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:wheel-linear" /></template>
<style>
.bheqf2b1q {
  d: path("M9 17.1962L11 13.7321");
}

.h_tsn8bxt {
  cx: 12px;
  cy: 12px;
  r: 2px;
}

.hdj33kbau {
  d: path("M11 10.2681L9 6.80396");
}

.hrlkjybrs {
  d: path("M6 12L10 12");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k6xbvzbvu {
  d: path("M14 12L18 12");
}

.kgwbfcbts {
  d: path("M15 17.1963L13 13.7322");
}

.shu3xdl9q {
  cx: 12px;
  cy: 12px;
  r: 10px;
}

.v90gbqbox {
  cx: 12px;
  cy: 12px;
  r: 6px;
}

.y8jdc-bgt {
  d: path("M13 10.2681L15 6.80403");
}

</style>
