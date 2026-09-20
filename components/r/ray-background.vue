<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGcguMZbHl)" class="r4i437pya"/><path class="ar91v5opk"/><path class="sp99i-2se"/><path class="gnwz0ua-f"/></g><defs><linearGradient id="SVGcguMZbHl" x1="19.099" x2="4.129" y1="8.005" y2="14.149" gradientUnits="userSpaceOnUse"><stop class="f314_iu6t"/><stop offset=".49" class="vwzpv59ae"/><stop offset="1" class="upr4icqsm"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:ray-background" /></template>
<style>
.ar91v5opk {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.222 10.222v5.334L12 19.005l-6.222-3.45v-7.11L12 4.982l4.895 2.602l.738-.415L12 4L4.889 8v8l7.11 4l7.112-4V9.59z");
}

.f314_iu6t {
  stop-color: var(--svg-color--c200fb, #c200fb);
}

.ft5dv1b6b {
  fill: none;
}

.gnwz0ua-f {
  fill: var(--svg-color--fff, #fff);
  d: path("M15.339 15.555h-1.55l-.959-1.684c.38-.023 1.031-.178 1.399-.377zm2.217-6.649l.777.428l.778-.428v-.904l-.777-.446l-.778.446z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.sp99i-2se {
  fill: var(--svg-color--fff, #fff);
  d: path("M10.666 15.555H9.333v-3.556h3.111c.676-.007 1.332-.451 1.333-1.137c.009-.674-.664-1.09-1.333-1.085H9.333V8.444h3.373c1.424 0 2.394 1.067 2.405 2.418c.012 1.46-1.143 2.47-2.763 2.47h-1.682z");
}

.upr4icqsm {
  stop-color: var(--svg-color--5ac4be, #5ac4be);
}

.vwzpv59ae {
  stop-color: var(--svg-color--3773fe, #3773fe);
}

</style>
