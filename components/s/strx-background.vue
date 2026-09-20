<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVG6DDlneTI)" class="r4i437pya"/><path class="rh6atx47v"/></g><defs><linearGradient id="SVG6DDlneTI" x1="6.307" x2="17.659" y1="5.971" y2="16.989" gradientUnits="userSpaceOnUse"><stop class="os8ml0b3o"/><stop offset=".69" class="i9_u8pv0w"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:strx-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.i9_u8pv0w {
  stop-color: var(--svg-color--4950d4, #4950d4);
}

.os8ml0b3o {
  stop-color: var(--svg-color--73d8e2, #73d8e2);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.rh6atx47v {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.019 9.93L5.002 4l11.836 2.259zM10.616 20L4.47 4.612l7.248 5.976zm7.887-13.553l-5.609 4.612h4.4l-5.882 8.71l8.117-9.651h-3.905z");
}

</style>
