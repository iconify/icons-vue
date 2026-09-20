<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVG6xy4Mb7c)" class="r4i437pya"/><path class="u8550mp4m"/></g><defs><linearGradient id="SVG6xy4Mb7c" x1="12" x2="12" y1="4" y2="20" gradientUnits="userSpaceOnUse"><stop class="dltdc5rjj"/><stop offset="1" class="oakdr_dxm"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:solid-background" /></template>
<style>
.dltdc5rjj {
  stop-color: var(--svg-color--00c0d6, #00c0d6);
}

.ft5dv1b6b {
  fill: none;
}

.oakdr_dxm {
  stop-color: var(--svg-color--10f9db, #10f9db);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.u8550mp4m {
  fill: var(--svg-color--fff, #fff);
  d: path("M12 20a8 8 0 1 0 0-16a8 8 0 0 0 0 16");
}

</style>
