<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGfW6KMeiG)" class="r4i437pya"/><path class="m3y-cpbnr"/></g><defs><linearGradient id="SVGfW6KMeiG" x1="12" x2="12" y1="4" y2="20" gradientUnits="userSpaceOnUse"><stop class="rzu22jbkt"/><stop offset="1" class="b5xsunz4d"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:wifi-background" /></template>
<style>
.b5xsunz4d {
  stop-color: var(--svg-color--8c54fe, #8c54fe);
}

.ft5dv1b6b {
  fill: none;
}

.m3y-cpbnr {
  fill: var(--svg-color--fff, #fff);
  d: path("M6.423 4h-1.6c-.213 0-.347.192-.267.363l2.81 5.877c.049.096.15.16.268.16h1.834a.28.28 0 0 0 .256-.15l2.064-3.818a.14.14 0 0 1 .128-.075h.17a.13.13 0 0 1 .123.075l2.086 3.824c.053.085.15.144.256.144h1.824a.28.28 0 0 0 .261-.16l2.806-5.877c.085-.171-.054-.363-.262-.363h-1.514c-.054 0-.107.027-.128.075l-1.846 3.717c-.101.197-.405.203-.512.01l-2.016-3.658a.29.29 0 0 0-.25-.144h-1.782a.28.28 0 0 0-.25.144L8.87 7.797c-.107.192-.416.187-.517-.01L6.55 4.075A.14.14 0 0 0 6.423 4m0 16h-1.6c-.213 0-.347-.197-.267-.373l2.81-5.872a.3.3 0 0 1 .268-.16h1.834a.29.29 0 0 1 .256.149l2.064 3.819a.14.14 0 0 0 .128.074h.17a.13.13 0 0 0 .123-.074l2.086-3.819a.29.29 0 0 1 .256-.144h1.824c.112 0 .213.053.261.15l2.806 5.882c.085.17-.054.368-.262.368h-1.514a.14.14 0 0 1-.128-.08l-1.846-3.717c-.101-.198-.405-.203-.512-.006l-2.016 3.659a.28.28 0 0 1-.25.144h-1.782a.28.28 0 0 1-.25-.144L8.87 16.203c-.107-.198-.416-.192-.517.01L6.55 19.92a.15.15 0 0 1-.128.08m-1.067-8.533c-.16 0-.288.112-.288.256v.554c0 .144.128.256.288.256h13.29c.16 0 .289-.112.289-.256v-.554c0-.144-.128-.256-.288-.256z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.rzu22jbkt {
  stop-color: var(--svg-color--0176f0, #0176f0);
}

</style>
