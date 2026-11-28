<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="diyy7fb7k"/><path class="eqjw64pds"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:user-heart-sharp-fill" /></template>
<style>
.diyy7fb7k {
  fill: currentColor;
  d: path("M11 22H2C1.44772 22 1 21.5523 1 21V19C1 15.134 4.13402 12 8 12H11V22ZM9 2C11.2092 2 13 3.79082 13 6C13 8.20918 11.2092 10 9 10C6.79094 10 5 8.20921 5 6C5 3.79079 6.79094 2 9 2Z");
  stroke: none;
}

.eqjw64pds {
  d: path("M18 21C16.175 19.4846 14 18.1806 14 16.2361C14 15.0011 15.0745 14 16.4 14C17 14 17.537 14.2123 18 14.5833C18.463 14.2123 19 14 19.6 14C20.9255 14 22 15.0011 22 16.2361C22 18.1806 19.825 19.4846 18 21Z");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
