<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGvj4khbBq)" class="r4i437pya"/><path class="whw9vrelq"/><path class="xdnr83_ok"/></g><defs><linearGradient id="SVGvj4khbBq" x1="9.249" x2="18.748" y1="6.774" y2="13.03" gradientUnits="userSpaceOnUse"><stop class="ev_507bww"/><stop offset="1" class="i8h276bpu"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:rare-background" /></template>
<style>
.ev_507bww {
  stop-color: var(--svg-color--e7f88f, #e7f88f);
}

.ft5dv1b6b {
  fill: none;
}

.i8h276bpu {
  stop-color: var(--svg-color--50f0f8, #50f0f8);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.whw9vrelq {
  fill: var(--svg-color--000, #000);
  d: path("M11.81 4h1.143v1.905h3.058v3.809h-.35c-.286-1.566-2.034-3.459-3.688-3.459c-1.238 0-2.605.602-2.605 1.718c0 1.36 1.444 2.084 2.442 2.541v2.876a10 10 0 0 1-.861-.332c-1.612-.761-3.372-1.752-3.33-3.725c.042-2.152 1.905-3.428 4.19-3.428z");
}

.xdnr83_ok {
  fill: var(--svg-color--000, #000);
  d: path("M11.81 18.095h.564l-4.057-.007h-.316v-4.183h.316c.404 1.867 1.989 3.81 4.183 3.81c1.588 0 2.285-.953 2.213-2.332c-.046-.838-.876-1.215-1.76-1.588v-2.938q.202.09.396.199c1.486.674 3.032 1.485 3.032 3.432c0 2.464-2.144 3.607-3.809 3.607l.381-.019V20H11.81z");
}

</style>
