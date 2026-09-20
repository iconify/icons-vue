<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="wvpuuk5ak"/><path fill="url(#SVGRmDsgdgw)" class="l5lic11fc"/><path fill="url(#SVG6tziOcok)" class="h3ulchc8p"/><defs><linearGradient id="SVGRmDsgdgw" x1="8.865" x2="20.52" y1="10.485" y2="10.485" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="stui2mbih"/></linearGradient><linearGradient id="SVG6tziOcok" x1="13.054" x2="3.397" y1="13.515" y2="13.515" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="stui2mbih"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:ubsn" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.h3ulchc8p {
  d: path("M13.875 14.625H3v-1.5h10.875z");
}

.l5lic11fc {
  d: path("M7.875 9.375H21v1.5H7.875z");
}

.stui2mbih {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0;
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.wvpuuk5ak {
  fill: var(--svg-color--fff, #fff);
  d: path("m13.875 14.625l-6-3.75v-1.5l6 3.75z");
  opacity: var(--svg-opacity--0-8, 0.8);
}

</style>
