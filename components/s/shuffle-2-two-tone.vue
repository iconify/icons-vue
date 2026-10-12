<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="m9rhf2bws"/><path class="m48xordxs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:shuffle-2-two-tone" /></template>
<style>
.m48xordxs {
  d: path("M3 21L20.4 3.6M15 3L20.5 3C20.7761 3 21 3.2239 21 3.5L21 9");
}

.m9rhf2bws {
  stroke-opacity: 0.4;
  d: path("M3 3L9.1716 9.1716M14.8284 14.8284L20.4 20.4M15 21L20.5 21C20.7761 21 21 20.7761 21 20.5L21 15");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
