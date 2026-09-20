<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="j86rmkdgl"/><path class="h19o7e-ax"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:sudo-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.h19o7e-ax {
  fill: var(--svg-color--fff, #fff);
  d: path("M5.573 6.889H4l1.907 5.07L4 17.112h1.573l1.89-5.151zm12.854 0H20l-1.907 5.07L20 17.112h-1.573l-1.894-5.151zm-3.418 4h-1.356c0-.445-.658-.89-1.524-.89c-.867 0-1.667.188-1.667 1.17c0 .977.92.817 2.89 1.266c1.572.36 1.76 1.445 1.76 2.102c0 .934-.396 2.13-2.983 2.13c-2.747 0-3.302-1.565-3.236-2.223h1.485c0 .787.813 1.334 1.75 1.334c.934 0 1.699-.445 1.699-1.245c0-.795-.64-.982-2.765-1.324c-1.698-.271-1.986-1.476-1.92-2.04c-.066-.69.418-2.058 2.885-2.058s3.017 1.156 2.982 1.778");
}

.j86rmkdgl {
  fill: var(--svg-color--b9b9ff, #b9b9ff);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
