<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="mej7b4bsh"/><path class="eqjw64pds"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:user-heart-duotone" /></template>
<style>
.eqjw64pds {
  d: path("M18 21C16.175 19.4846 14 18.1806 14 16.2361C14 15.0011 15.0745 14 16.4 14C17 14 17.537 14.2123 18 14.5833C18.463 14.2123 19 14 19.6 14C20.9255 14 22 15.0011 22 16.2361C22 18.1806 19.825 19.4846 18 21Z");
}

.mej7b4bsh {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M10 13C10.5523 13 11 13.4477 11 14V21C11 21.5523 10.5523 22 10 22H3C1.89542 22 1 21.1046 1 20C1 16.134 4.13402 13 8 13H10ZM9 3C11.2092 3 13 4.79082 13 7C13 9.20918 11.2092 11 9 11C6.79094 11 5 9.20921 5 7C5 4.79079 6.79094 3 9 3Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
