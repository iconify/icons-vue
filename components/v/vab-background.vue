<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="beaf9ac8r"/><path fill="url(#SVGQ0jB3w8U)" class="pb1v0cb9n"/></g><defs><linearGradient id="SVGQ0jB3w8U" x1="6.119" x2="12.461" y1="6.59" y2="18.357" gradientUnits="userSpaceOnUse"><stop class="bqbum-ggb"/><stop offset=".82" class="ch02ot2zw"/><stop offset="1" class="sydswib2t"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:vab-background" /></template>
<style>
.beaf9ac8r {
  fill: var(--svg-color--fff, #fff);
  d: path("M24 0H0v24h24z");
}

.bqbum-ggb {
  stop-color: var(--svg-color--470180, #470180);
}

.ch02ot2zw {
  stop-color: var(--svg-color--ef62c9, #ef62c9);
}

.ft5dv1b6b {
  fill: none;
}

.pb1v0cb9n {
  d: path("M13.096 18.634a.894.894 0 0 1-1.52 0L4.12 6.214c-.339-.565.085-1.27.762-1.27h13.357c1.364 0 2.207 1.425 1.515 2.55l-1.623 2.648c-.63 1.03-1.717 1.388-2.964 1.388H10.09a.46.46 0 0 0-.443.47c.01.283.236.47.443.47h3.683a1.711 1.711 0 0 1 1.459 2.603z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.sydswib2t {
  stop-color: var(--svg-color--ffccf7, #ffccf7);
}

</style>
