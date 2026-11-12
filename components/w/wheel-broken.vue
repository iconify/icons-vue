<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="h_tsn8bxt"/><path class="hrlkjybrs"/><path class="k6xbvzbvu"/><path class="bheqf2b1q"/><path class="y8jdc-bgt"/><path class="kgwbfcbts"/><path class="hdj33kbau"/><path class="ko6o-6b9b"/><path class="ew92mhbfo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:wheel-broken" /></template>
<style>
.bheqf2b1q {
  d: path("M9 17.1962L11 13.7321");
}

.ew92mhbfo {
  d: path("M15 17.1973C14.1175 17.7078 13.0929 18 12 18C8.68629 18 6 15.3137 6 12C6 8.68629 8.68629 6 12 6C15.3137 6 18 8.68629 18 12C18 13.0929 17.7078 14.1175 17.1973 15");
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

.ko6o-6b9b {
  d: path("M7 3.33782C8.47087 2.48697 10.1786 2 12 2C17.5228 2 22 6.47715 22 12C22 17.5228 17.5228 22 12 22C6.47715 22 2 17.5228 2 12C2 10.1786 2.48697 8.47087 3.33782 7");
}

.y8jdc-bgt {
  d: path("M13 10.2681L15 6.80403");
}

</style>
