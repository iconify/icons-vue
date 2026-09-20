<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVG930RGd6f)" class="r4i437pya"/><path class="xuq-psmiw"/></g><defs><linearGradient id="SVG930RGd6f" x1="19.059" x2="7.722" y1="8.659" y2="16.598" gradientUnits="userSpaceOnUse"><stop class="b48k622ry"/><stop offset="1" class="qjhjtlxfw"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:shido-background" /></template>
<style>
.b48k622ry {
  stop-color: var(--svg-color--009cff, #009cff);
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.qjhjtlxfw {
  stop-color: var(--svg-color--0070ff, #0070ff);
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.xuq-psmiw {
  fill: var(--svg-color--fff, #fff);
  d: path("M14.019 6A2.007 2.007 0 0 1 12 8a2.01 2.01 0 0 1-2.019-2a2.01 2.01 0 0 1 2.02-2c1.115 0 2.018.894 2.018 2m-5.313 5.059v1.515l2.07 1.308l1.224-.8zm6.588 0v1.515l-2.07 1.308l-1.224-.8zm-2.136-3.12a2.245 2.245 0 0 0 1.059-2.424l4.842 2.697v2.607l-2.353 1.26V9.912l-3.548-1.977zm3.548 5.416l2.353-1.284v4L12 20l-7.059-3.93v-4.014l2.353 1.285v1.803L12 17.755l4.706-2.611zM4.941 8.212V10.8l2.353 1.266V9.91l3.549-1.977a2.245 2.245 0 0 1-1.06-2.419z");
}

</style>
