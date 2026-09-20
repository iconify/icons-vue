<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGWvHSzbeW)" class="r4i437pya"/><path class="h1znzh30z"/></g><defs><linearGradient id="SVGWvHSzbeW" x1="12.012" x2="12.012" y1="3.987" y2="19.998" gradientUnits="userSpaceOnUse"><stop class="ut702abgz"/><stop offset=".36" class="znhwt_b9m"/><stop offset=".71" class="wgjwl5pci"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:rxd-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.h1znzh30z {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.39 17.922a8.005 8.005 0 0 0-9.102-13.01a8 8 0 0 0-2.53 2.077H4.005L6.748 9.55c.3.285.7.44 1.116.44h4.823c.73 0 1.326.52 1.326 1.251s-.745 1.251-1.476 1.251h-.525l2.497 2.502c1.656 0 3.007-1.501 3.007-3.753v-.07a4.183 4.183 0 0 0-4.178-4.183H6.283a7.605 7.605 0 1 1 10.853 10.618l.25.315zM6.309 12.793l6.604 6.755a7.61 7.61 0 0 1-8.467-6.781a7.6 7.6 0 0 1 .647-3.927l-.286-.35a8.006 8.006 0 0 0 8.457 11.408l.1.096h5.154L9.66 10.992H7.058c-.926 0-1.39 1.13-.74 1.796z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.ut702abgz {
  stop-color: var(--svg-color--4d8fb2, #4d8fb2);
}

.wgjwl5pci {
  stop-color: var(--svg-color--fff4c4, #fff4c4);
}

.znhwt_b9m {
  stop-color: var(--svg-color--35c6f3, #35c6f3);
}

</style>
