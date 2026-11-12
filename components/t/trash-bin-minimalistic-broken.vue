<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="kvdjm4bsr"/><path class="fh6a-dbrt"/><path class="nr-pbwdvr"/><path class="p2-mbsbue"/><path class="w8w5t9ikw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:trash-bin-minimalistic-broken" /></template>
<style>
.fh6a-dbrt {
  d: path("M20.5001 6H3.5");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kvdjm4bsr {
  d: path("M9.1709 4C9.58273 2.83481 10.694 2 12.0002 2C13.3064 2 14.4177 2.83481 14.8295 4");
}

.nr-pbwdvr {
  d: path("M5.1665 8.5L5.62644 15.3991C5.80344 18.054 5.89194 19.3815 6.75694 20.1907C7.62195 21 8.95235 21 11.6132 21H12.3865C15.0473 21 16.3777 21 17.2427 20.1907C18.1077 19.3815 18.1962 18.054 18.3732 15.3991M18.6332 11.5L18.8332 8.5");
}

.p2-mbsbue {
  d: path("M9.5 11L10 16");
}

.w8w5t9ikw {
  d: path("M14.5 11L14 16");
}

</style>
