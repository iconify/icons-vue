<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="k917zqb6e"/><path class="ds0j4aclk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:rotate-clockwise-2-broken" /></template>
<style>
.ds0j4aclk {
  d: path("M13.0711 14.9289C11.6904 13.5482 11 12.8579 11 12C11 11.4039 11.3333 10.8887 12 10.1665C12.2927 9.8494 12.6498 9.4924 13.0711 9.0711C13.4924 8.6498 13.8494 8.2927 14.1665 8C14.8887 7.3333 15.4039 7 16 7C16.8579 7 17.5482 7.6904 18.9289 9.0711C20.3096 10.4518 21 11.1421 21 12C21 12.8579 20.3096 13.5482 18.9289 14.9289C17.5482 16.3096 16.8579 17 16 17C15.1421 17 14.4518 16.3096 13.0711 14.9289Z");
}

.jx0p4fbya {
  fill: none;
  stroke: currentColor;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k917zqb6e {
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8 7.4286V4H4.25M8 4C4.875 6.8571 3 9 3 12C3 13.3312 3.345 14.7186 4.0126 16M8 20C7.2532 19.6058 6.5855 19.1285 6 18.5907");
}

</style>
