<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGCfieOe9l)" class="r4i437pya"/><path class="dp5l9mb1d"/><path class="ppfugbbly"/></g><defs><linearGradient id="SVGCfieOe9l" x1="15.52" x2="10.691" y1="10.474" y2="10.474" gradientUnits="userSpaceOnUse"><stop class="f-skp2ple"/><stop offset="1" class="lvsvg0b2y"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:route-background" /></template>
<style>
.dp5l9mb1d {
  fill: var(--svg-color--fff, #fff);
  d: path("M8.914 5.156a.257.257 0 0 1-.008-.35a2.33 2.33 0 0 1 3.423-.113l1.768 1.756a3.7 3.7 0 0 1 .043 5.145l-2.257 2.346l2.35 2.43a2.585 2.585 0 0 1 .008 3.557a.23.23 0 0 1-.337 0l-3.365-3.402a3.7 3.7 0 0 1 .009-5.162l2.24-2.253l-3.874-3.958z");
}

.f-skp2ple {
  stop-color: var(--svg-color--fe8664, #fe8664);
}

.ft5dv1b6b {
  fill: none;
}

.lvsvg0b2y {
  stop-color: var(--svg-color--ff3b56, #ff3b56);
}

.ppfugbbly {
  fill: var(--svg-color--fff, #fff);
  d: path("m11.285 10.617l1.499-1.508a2.74 2.74 0 0 1 .374 3.504l-1.275 1.322c-.48-.484-1.365-1.642-.623-3.26z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

</style>
