<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGnOtCTcZi)" class="zxn6lkbsq"/><path fill="url(#SVGT1bGXPGl)" class="vq25p1o3a"/><path fill="url(#SVGOqB6Hc5H)" class="g-frv3bpq"/><defs><linearGradient id="SVGnOtCTcZi" x1="5.808" x2="21.001" y1="9.86" y2="9.86" gradientUnits="userSpaceOnUse"><stop class="o419w2mdk"/><stop offset="1" class="iiscboqnu"/></linearGradient><linearGradient id="SVGT1bGXPGl" x1="5.142" x2="19.209" y1="7.639" y2="7.639" gradientUnits="userSpaceOnUse"><stop class="un5nngb2s"/><stop offset="1" class="mxxcsv8or"/></linearGradient><linearGradient id="SVGOqB6Hc5H" x1="12.845" x2="9.29" y1="10.376" y2="16.666" gradientUnits="userSpaceOnUse"><stop class="d1xo4i2zc"/><stop offset="1" class="mwcknuj7p"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:vlxpad" /></template>
<style>
.d1xo4i2zc {
  stop-color: var(--svg-color--01dbc0, #01dbc0);
}

.ft5dv1b6b {
  fill: none;
}

.g-frv3bpq {
  d: path("m13 12l-1-2.5l-3.25 5.75A26 26 0 0 1 10 18s1.906-3.9 3-6");
}

.iiscboqnu {
  stop-color: var(--svg-color--02cbc5, #02cbc5);
}

.mwcknuj7p {
  stop-color: var(--svg-color--03acd3, #03acd3);
}

.mxxcsv8or {
  stop-color: var(--svg-color--01e8ba, #01e8ba);
}

.o419w2mdk {
  stop-color: var(--svg-color--0753f7, #0753f7);
}

.un5nngb2s {
  stop-color: var(--svg-color--02a7a1, #02a7a1);
}

.vq25p1o3a {
  d: path("M21 5.999H10.5l1.25 2.5h4.5l-.5 1H12l1 2.5h4z");
}

.zxn6lkbsq {
  d: path("M5.735 5.999H3l5 8.5l3.75-6L10.5 6l-2.3 4.1z");
}

</style>
