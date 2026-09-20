<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGNEiCAcUD)" class="r4i437pya"/><path class="mf4pnlbit"/><path class="rvs6wlb1t"/><path class="dvswfsb9n"/><path class="u8vzbej5j"/></g><defs><linearGradient id="SVGNEiCAcUD" x1="11.997" x2="11.997" y1="4.006" y2="20" gradientUnits="userSpaceOnUse"><stop class="bwz5beuwo"/><stop offset=".54" class="y8d0ac9pe"/><stop offset="1" class="yuvxxfndb"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:sail-background" /></template>
<style>
.bwz5beuwo {
  stop-color: var(--svg-color--ff9c00, #ff9c00);
}

.dvswfsb9n {
  fill: var(--svg-color--fff, #fff);
  d: path("M5.514 17.75v-1.253s.26-.498 1.037-.498c1.99 0 7.948 2.733 9.86 2.75c1.102.01 1.73-.8 2.075-1.249c-.346.666-1.366 2.076-3.027 2.076c-2.075 0-5.894-2.327-8.908-2.327c-.622 0-.95.333-1.037.502");
}

.ft5dv1b6b {
  fill: none;
}

.mf4pnlbit {
  fill: var(--svg-color--fff, #fff);
  d: path("M15.892 18.003c-4.982-6.201-3.46-10.586-2.076-12.004c-3.736 3.403-2.421 8.752-1.297 11c1.038.602 2.681.917 3.373 1z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.rvs6wlb1t {
  fill: var(--svg-color--fff, #fff);
  d: path("M7.07 15c.208-4.401 4.584-9.167 6.746-11C9.457 9.6 10.789 14.832 12 16.748z");
}

.u8vzbej5j {
  fill: var(--svg-color--fff, #fff);
  d: path("M6.698 17.475c-1.037 0-1.011 1.215-.752 1.686c0-.238.216-.843.752-.843c.761-.005 5.726 1.06 8.329 1.682c-2.378-.843-6.486-2.525-8.329-2.525");
}

.y8d0ac9pe {
  stop-color: var(--svg-color--fed087, #fed087);
}

.yuvxxfndb {
  stop-color: var(--svg-color--ff9d00, #ff9d00);
}

</style>
