<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="cfbnhhf2m"/><path class="sudo-1bgw"/><path class="p38jjsbgx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:wifi-plus-sharp-two-tone" /></template>
<style>
.cfbnhhf2m {
  stroke-opacity: 0.4;
  d: path("M6.588 15.6853L7.3333 15.0186C8.0667 14.3626 9.0161 14 10 14C10.7121 14 11.4113 14.1901 12.0253 14.5506L12.519 14.8405M3.9214 12.7039L4.6667 12.0372C6.1334 10.7253 8.0322 10 10 10C11.4242 10 12.8225 10.3802 14.0506 11.1013L14.5443 11.3911M1.6667 9.3538L2 9.0557C4.2001 7.0879 7.0483 6 10 6C12.606 6 15.1411 6.8483 17.2223 8.4167L17.6204 8.7168");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.p38jjsbgx {
  d: path("M19 11L19 19M15 15L23 15");
}

.sudo-1bgw {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M11 18C11 18.5523 10.5523 19 10 19C9.4477 19 9 18.5523 9 18C9 17.4477 9.4477 17 10 17C10.5523 17 11 17.4477 11 18Z");
  stroke: none;
}

</style>
