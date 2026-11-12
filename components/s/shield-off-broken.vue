<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rsrhfac5n"/><path class="gzf-uobcm"/><path class="qe43_7gfs"/><path class="ymfztty9o"/><path class="riowoxbtk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:shield-off-broken" /></template>
<style>
.gzf-uobcm {
  d: path("M3 10.4167C3 7.2191 3 5.6203 3.3775 5.0824C3.75491 4.54463 5.25757 4.03025 8.26269 3.00155L8.2649 3.0008L8.8377 2.8047C10.405 2.2682 11.1886 2 12 2C12.8114 2 13.595 2.2682 15.1623 2.8047L15.7351 3.0008L15.739 3.00215C17.5312 3.61563 18.789 4.04616 19.5921 4.4079");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qe43_7gfs {
  d: path("M3.19238 14C3.56498 15.8678 4.44148 17.3421 5.50408 18.4955");
}

.riowoxbtk {
  d: path("M7.35156 20.1038C8.23876 20.7294 9.13376 21.1934 9.89826 21.5274L9.89851 21.5275C10.6197 21.8425 10.9805 22.0001 11.9997 22.0001C13.0188 22.0001 13.3796 21.8425 14.1008 21.5275L14.1011 21.5274C14.6793 21.2748 15.3321 20.9479 15.9997 20.5329");
}

.rsrhfac5n {
  d: path("M22 2L2 22");
}

.ymfztty9o {
  d: path("M20.9383 6.51733C21 7.39773 21 8.66813 21 10.4167V11.9914C21 14.4963 20.1632 16.4284 19 17.9041");
}

</style>
