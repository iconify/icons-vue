<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGbLxMdcZl)" class="r4i437pya"/><path class="rddn_pblr"/></g><defs><linearGradient id="SVGbLxMdcZl" x1="4" x2="18.006" y1="4.942" y2="20.817" gradientUnits="userSpaceOnUse"><stop class="zrinmvwby"/><stop offset="1" class="o9-x5-btj"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:matic-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.o9-x5-btj {
  stop-color: var(--svg-color--7442db, #7442db);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.rddn_pblr {
  fill: var(--svg-color--fff, #fff);
  d: path("M7.925 9.254a1 1 0 0 1 1.007 0l2.3 1.375l1.563.894l2.306 1.374c.292.178.678.178 1.002 0l1.831-1.073c.296-.179.654-.508.654-.866V8.84c0-.357-.33-.687-.659-.866L16.132 6.93a1 1 0 0 0-1.003 0l-1.802 1.044c-.292.18-.386.509-.386.866v1.37l-1.412-.923V7.91c0-.358-.094-.687.236-.866L15.1 5.076a1 1 0 0 1 1.002 0l3.393 1.967a.97.97 0 0 1 .504.87v3.972a.98.98 0 0 1-.504.866l-3.393 1.967a1 1 0 0 1-1.002 0l-2.306-1.341l-1.562-.927l-2.306-1.342a1 1 0 0 0-1.002 0l-1.798 1.045c-.296.179-.715.508-.715.866v2.118c0 .357.39.687.715.866l1.798 1.073c.296.178.682.178 1.007 0l1.797-1.045c.297-.179.8-.508.8-.866v-1.37l1.412.923v1.374c0 .358-.32.687-.645.866L8.894 18.92a.98.98 0 0 1-1.002 0l-3.393-1.967A1.04 1.04 0 0 1 4 16.092V12.12c0-.357.179-.687.504-.866z");
}

.zrinmvwby {
  stop-color: var(--svg-color--8f34c2, #8f34c2);
}

</style>
