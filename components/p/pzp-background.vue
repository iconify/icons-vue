<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGPFbrhbPE)" class="r4i437pya"/><path class="tbwc059um"/><path class="qf0z19uql"/><path class="jq5-jfi3j"/></g><defs><linearGradient id="SVGPFbrhbPE" x1="7.551" x2="13.603" y1="5.344" y2="22.351" gradientUnits="userSpaceOnUse"><stop offset=".02" class="p9px83imy"/><stop offset=".54" class="uexu2qbpz"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:pzp-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.jq5-jfi3j {
  fill: var(--svg-color--fff, #fff);
  d: path("m12.471 9.29l-1.257 2.177c-.232.396-.547.827-.547 1.2c0 .89.618 1.392.889 1.556c.52-.734.715-1.027 1.222-1.773a2.92 2.92 0 0 0 .556-1.934c0-1.329-1.232-2.031-1.778-2.071H9.382a2 2 0 0 1-1.826-1.311c0 1.084.902 1.755 2.017 1.755h1.983c.342 0 .667.223.915.4");
}

.p9px83imy {
  stop-color: var(--svg-color--d4964b, #d4964b);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.qf0z19uql {
  fill: var(--svg-color--fff, #fff);
  d: path("M7.556 5.777v1.356c0 1.084.902 1.756 2.017 1.756h1.89c.404 0 .8.124.946.186a291 291 0 0 0-3.467 3.658c-.324.373-1.386 1.511-1.386 2.951a1.973 1.973 0 0 0 1.702 2.094h7.187v-1.356c0-1.084-.902-1.756-2.018-1.756h-1.76c-.4 0-.938-.124-1.107-.186c.902-.942 2.911-3.138 3.311-3.534c.507-.489 1.578-1.413 1.578-3.137a2.006 2.006 0 0 0-1.578-2.032z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.tbwc059um {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.556 17.777h.889v1.73c0 .27-.2.493-.445.493c-.244 0-.444-.223-.444-.494zm-1.779-.887h.89v1.729c0 .27-.2.493-.445.493s-.445-.222-.445-.493zm2.668-10.668h-.89V4.493c0-.27.2-.493.445-.493s.444.222.444.493zm1.778.445h-.889v-1.73c0-.27.2-.493.444-.493c.245 0 .445.223.445.494z");
}

.uexu2qbpz {
  stop-color: var(--svg-color--ffed87, #ffed87);
}

</style>
