<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="p7ipgfm_g"/><path class="tc3vce78v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:rotate-clockwise-2-line-duotone" /></template>
<style>
.jx0p4fbya {
  fill: none;
  stroke: currentColor;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.p7ipgfm_g {
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8 7.4286V4H4.25M8 4C4.875 6.8571 3 9 3 12C3 15 4.7524 18.2857 8 20");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.tc3vce78v {
  d: path("M13.0711 14.9289C11.6904 13.5482 11 12.8579 11 12C11 11.1421 11.6904 10.4518 13.0711 9.0711C14.4518 7.6904 15.1421 7 16 7C16.8579 7 17.5482 7.6904 18.9289 9.0711C20.3096 10.4518 21 11.1421 21 12C21 12.8579 20.3096 13.5482 18.9289 14.9289C17.5482 16.3096 16.8579 17 16 17C15.1421 17 14.4518 16.3096 13.0711 14.9289Z");
}

</style>
