<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="aahgoh0mn"/><path class="av8z7db_k"/><path class="ee9a_dqqh"/><path class="wruzqvbcf"/><path class="w8fcmcc3c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:station-minimalistic-line-duotone" /></template>
<style>
.aahgoh0mn {
  d: path("M13.25 8.75C13.25 9.44036 12.6904 10 12 10C11.3096 10 10.75 9.44036 10.75 8.75C10.75 8.05964 11.3096 7.5 12 7.5C12.6904 7.5 13.25 8.05964 13.25 8.75Z");
}

.av8z7db_k {
  d: path("M7.00778 14C5.76601 12.7269 5 10.981 5 9.05473C5 5.15851 8.13401 2 12 2C15.866 2 19 5.15851 19 9.05473C19 10.9647 18.2468 12.6975 17.0235 13.9677");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.ee9a_dqqh {
  d: path("M8.9876 12.0045C8.25248 11.2422 7.7998 10.2017 7.7998 9.05474C7.7998 6.71701 9.68021 4.8219 11.9998 4.8219C14.3194 4.8219 16.1998 6.71701 16.1998 9.05474C16.1998 10.1855 15.7599 11.2127 15.0431 11.972");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.w8fcmcc3c {
  d: path("M14.5 17.5H9.5");
}

.wruzqvbcf {
  stroke-linejoin: round;
  d: path("M16 22L12 10L8 22");
}

</style>
