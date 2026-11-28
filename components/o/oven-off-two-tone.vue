<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="tpprqygxs"/><path class="qpj_722nl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:oven-off-two-tone" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qpj_722nl {
  d: path("M20 20C20 21.105 19.105 22 18 22H6C4.895 22 4 21.105 4 20V6C4 5.413 4.126 4.856 4.353 4.353M4 10H10M9 14H14M2 2L22 22");
}

.tpprqygxs {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M20.872 20.872C20.487 22.136 19.321 23 18 23H6C4.343 23 3 21.657 3 20V6C2.999 5.164 3.208 4.342 3.608 3.608L20.872 20.872ZM7.589 1.017C7.726 1.006 7.863 1 8 1H16C18.761 1 21 3.239 21 6V14.343H20.98C20.98 14.884 20.542 15.323 20 15.323C19.74 15.323 19.491 15.22 19.307 15.036L19.293 15.05L6.963 2.72L6.977 2.706C6.793 2.523 6.69 2.273 6.69 2.013C6.69 1.503 7.082 1.078 7.591 1.037L7.589 1.017Z");
  stroke: none;
}

</style>
