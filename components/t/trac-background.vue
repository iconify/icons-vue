<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGW0TOKCPV)" class="r4i437pya"/><path class="pzarwfb3s"/></g><defs><linearGradient id="SVGW0TOKCPV" x1="5.654" x2="18.44" y1="7.654" y2="15.777" gradientUnits="userSpaceOnUse"><stop class="sqmwf1uff"/><stop offset="1" class="h2vaqubkn"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:trac-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.h2vaqubkn {
  stop-color: var(--svg-color--30c7b4, #30c7b4);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.pzarwfb3s {
  fill: var(--svg-color--fff, #fff);
  d: path("M12 4v3.98a4.02 4.02 0 1 0 3.075 6.61l3.045 2.56A7.97 7.97 0 0 1 12 20a8 8 0 0 1 0-16m3.775 9.39l3.735 1.38c-.165.435-.36.855-.6 1.26l-3.435-2.005a4 4 0 0 0 .3-.635m4.1-2.78Q20 11.286 20 12h-3.98c0-.24-.02-.47-.06-.7l3.92-.69zm-2.71-4.715c.36.3.685.63.985.99L15.09 9.43a4 4 0 0 0-.49-.5z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.sqmwf1uff {
  stop-color: var(--svg-color--4ccb88, #4ccb88);
}

</style>
