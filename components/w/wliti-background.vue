<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGCNlBMaFo)" class="r4i437pya"/><path class="efrxnjb4l"/><path class="s2v5rb-tj"/><path class="cd_2o0y4m"/><path class="i6wc0jb1n"/></g><defs><linearGradient id="SVGCNlBMaFo" x1="5.818" x2="20.559" y1="17.305" y2="9.747" gradientUnits="userSpaceOnUse"><stop class="k8ecu4b3n"/><stop offset=".67" class="b7z45jkeq"/><stop offset="1" class="kvy-wbhoo"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:wliti-background" /></template>
<style>
.b7z45jkeq {
  stop-color: var(--svg-color--6fc6a6, #6fc6a6);
}

.cd_2o0y4m {
  fill: var(--svg-color--fff, #fff);
  d: path("M8.5 7.975v4.845L4 15.4V5.5zM10 8.6v3.3l1.385-.825l2.865 1.65v-6.6zm5.69 4.95l-4.305 2.475L15.69 18.5L20 16.025z");
}

.efrxnjb4l {
  fill: var(--svg-color--fff, #fff);
  d: path("M8.5 12.775v5.1L4 15.4zm2.885-1.7L10 11.9v3.3l4.255-2.475z");
}

.ft5dv1b6b {
  fill: none;
}

.i6wc0jb1n {
  fill: var(--svg-color--fff, #fff);
  d: path("m9.95 8.6l5.744 3.3L20 9.425l-5.745-3.3z");
}

.k8ecu4b3n {
  stop-color: var(--svg-color--08a5b1, #08a5b1);
}

.kvy-wbhoo {
  stop-color: var(--svg-color--cae5c2, #cae5c2);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.s2v5rb-tj {
  fill: var(--svg-color--fff, #fff);
  d: path("M14.255 12.725L10 15.2v-3.3l-1.5.9v5.07l2.885-1.845l4.305-2.475z");
}

</style>
