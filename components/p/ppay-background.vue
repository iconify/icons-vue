<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGMNBHi2BO)" class="r4i437pya"/><path class="jfs4cyu4p"/></g><defs><linearGradient id="SVGMNBHi2BO" x1="12" x2="12" y1="4" y2="20" gradientUnits="userSpaceOnUse"><stop class="eftuxgn0j"/><stop offset="1" class="l5alyhbmh"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:ppay-background" /></template>
<style>
.eftuxgn0j {
  stop-color: var(--svg-color--fb4440, #fb4440);
}

.ft5dv1b6b {
  fill: none;
}

.jfs4cyu4p {
  fill: var(--svg-color--fff, #fff);
  d: path("m20 11.095l-.015-.035L12 13c-2.805-.67-7.715-1.87-7.985-1.94L4 11.11C4.45 7.11 7.86 4 12 4s7.55 3.1 8 7.095m-.085 2.37L12 14.25l-7.915-.79c.1.53.25 1.035.44 1.52L12 15.5l7.45-.465c.205-.5.365-1.025.465-1.57M18.65 16.51q-3.321.222-6.65.24c-2.15-.02-5.15-.235-6.73-.36q.39.593.885 1.11h11.69q.441-.463.805-.99m-1.955 1.99H7.3A8.05 8.05 0 0 0 12 20c1.75 0 3.375-.555 4.695-1.5");
}

.l5alyhbmh {
  stop-color: var(--svg-color--a72dc4, #a72dc4);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

</style>
