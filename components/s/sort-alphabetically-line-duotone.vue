<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="mm06y9blo"/><path class="vnxfpbb2u"/><path class="ez5yvcb0u"/><path class="o68l3dmms"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:sort-alphabetically-line-duotone" /></template>
<style>
.ez5yvcb0u {
  d: path("M8 17H3");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mm06y9blo {
  d: path("M13 7L3 7");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.o68l3dmms {
  stroke-linejoin: round;
  d: path("M12 17L13.6364 13.3636M21 17L19.3636 13.3636L16.5 7L13.6364 13.3636M13.6364 13.3636H19.3636");
}

.vnxfpbb2u {
  d: path("M10 12H3");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
