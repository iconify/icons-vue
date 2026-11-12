<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="aahgoh0mn"/><path class="r_k-6xaei"/><path class="wruzqvbcf"/><path class="w8fcmcc3c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:station-minimalistic-linear" /></template>
<style>
.aahgoh0mn {
  d: path("M13.25 8.75C13.25 9.44036 12.6904 10 12 10C11.3096 10 10.75 9.44036 10.75 8.75C10.75 8.05964 11.3096 7.5 12 7.5C12.6904 7.5 13.25 8.05964 13.25 8.75Z");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.r_k-6xaei {
  d: path("M7.00778 14C5.76601 12.7269 5 10.981 5 9.05473C5 5.15851 8.13401 2 12 2C15.866 2 19 5.15851 19 9.05473C19 10.9647 18.2468 12.6975 17.0235 13.9677M8.9878 12.0045C8.25268 11.2422 7.8 10.2017 7.8 9.05473C7.8 6.717 9.6804 4.82189 12 4.82189C14.3196 4.82189 16.2 6.717 16.2 9.05473C16.2 10.1855 15.76 11.2127 15.0432 11.972");
}

.w8fcmcc3c {
  d: path("M14.5 17.5H9.5");
}

.wruzqvbcf {
  stroke-linejoin: round;
  d: path("M16 22L12 10L8 22");
}

</style>
