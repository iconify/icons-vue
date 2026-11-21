<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="pzh2dybaq"/><path class="dniqbihkw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:pipe-section-two-tone" /></template>
<style>
.dniqbihkw {
  d: path("M20 2V10C20 15.5228 15.5228 20 10 20H2M13 2V10C13 11.6569 11.6569 13 10 13H2M6 22V11M22 6H11");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pzh2dybaq {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M17.7782 17.7782C15.7886 19.7677 13.0373 21 10 21L6 21C5.4477 21 5 20.5523 5 20L5 13C5 12.4477 5.4477 12 6 12L10 12C11.1046 12 12 11.1046 12 10L12 6C12 5.4477 12.4477 5 13 5L20 5C20.5523 5 21 5.4477 21 6L21 10C21 13.0373 19.7677 15.7886 17.7782 17.7782Z");
  stroke: none;
}

</style>
