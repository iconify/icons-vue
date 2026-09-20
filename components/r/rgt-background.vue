<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGXbP9Fe8U)" class="r4i437pya"/><path clip-rule="evenodd" class="qtj7flfzj"/><path clip-rule="evenodd" class="b_qdbo7cf"/><path clip-rule="evenodd" class="ic_c3bd4p"/></g><defs><linearGradient id="SVGXbP9Fe8U" x1="3.92" x2="20.08" y1="12.208" y2="12" gradientUnits="userSpaceOnUse"><stop class="slsok2bjq"/><stop offset="1" class="jstn7jpqh"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:rgt-background" /></template>
<style>
.b_qdbo7cf {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M8.942 17.298A6.118 6.118 0 1 0 15.06 6.702a6.118 6.118 0 0 0-6.118 10.596m3.058.348a5.647 5.647 0 1 0 0-11.294a5.647 5.647 0 0 0 0 11.294");
}

.ft5dv1b6b {
  fill: none;
}

.ic_c3bd4p {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M12 20a8 8 0 1 0 0-16a8 8 0 0 0 0 16m0-.47a7.53 7.53 0 1 0 0-15.06a7.53 7.53 0 1 0 0 15.06");
}

.jstn7jpqh {
  stop-color: var(--svg-color--f9f9f9, #f9f9f9);
  stop-opacity: 0;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.qtj7flfzj {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M12 16.705a4.706 4.706 0 1 0 0-9.411a4.706 4.706 0 0 0 0 9.411m0-.47a4.235 4.235 0 1 0 0-8.471a4.235 4.235 0 0 0 0 8.47");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.slsok2bjq {
  stop-color: var(--svg-color--f9f9f9, #f9f9f9);
}

</style>
