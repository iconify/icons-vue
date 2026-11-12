<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rsrhfac5n"/><path class="ni-d-ss2x"/><path class="f_fm0cb2b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:shield-off-linear" /></template>
<style>
.f_fm0cb2b {
  d: path("M20.938 6.51733C20.9997 7.39773 20.9997 8.66813 20.9997 10.4167V11.9914C20.9997 17.6294 16.7607 20.3655 14.1011 21.5273L14.1008 21.5274C13.3796 21.8425 13.0188 22 11.9997 22C10.9805 22 10.6197 21.8425 9.89851 21.5274L9.89826 21.5273C9.13376 21.1933 8.23876 20.7293 7.35156 20.1037");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ni-d-ss2x {
  d: path("M5.5045 18.4955C4.0865 16.9564 3 14.8458 3 11.9914V10.4167C3 7.2191 3 5.6203 3.3775 5.0824C3.75491 4.54463 5.25757 4.03025 8.26269 3.00155L8.2649 3.0008L8.8377 2.8047C10.405 2.2682 11.1886 2 12 2C12.8114 2 13.595 2.2682 15.1623 2.8047L15.7351 3.0008L15.739 3.00215C17.5312 3.61563 18.789 4.04616 19.5921 4.4079");
}

.rsrhfac5n {
  d: path("M22 2L2 22");
}

</style>
