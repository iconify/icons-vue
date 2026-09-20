<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGI5xR6dzJ)" class="r4i437pya"/><path clip-rule="evenodd" class="xdtcjcb7v"/></g><defs><linearGradient id="SVGI5xR6dzJ" x1="4.516" x2="19.229" y1="7.596" y2="7.596" gradientUnits="userSpaceOnUse"><stop class="zxclguriz"/><stop offset=".53" class="tr32s8myl"/><stop offset="1" class="y62nxg54e"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:witch-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.tr32s8myl {
  stop-color: var(--svg-color--1b67ff, #1b67ff);
}

.xdtcjcb7v {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M19.234 5.746a1.197 1.197 0 0 1 .66 1.61l-4.568 9.789a1.24 1.24 0 0 1-.74.861a1.32 1.32 0 0 1-1.699-.626L8.235 7.356a1.196 1.196 0 0 1 .66-1.61q.256-.105.513-.104h5.09c.706 0 1.27.528 1.27 1.177c0 .65-.564 1.177-1.27 1.177h-3.141l2.712 5.848l3.465-7.472a1.32 1.32 0 0 1 1.695-.626zm-8.63.626a1.3 1.3 0 0 0-.165-.259h4.059c.423 0 .8.315.8.706s-.377.707-.8.707h-3.362zm3.748 8.084l3.653-7.886a.79.79 0 0 1 1.022-.377c.39.165.565.598.395.965l-4.237 9.087zm-5.24-8.263c.39-.165.847.005 1.016.377l4.647 10.024c.175.372 0 .8-.395.965a.79.79 0 0 1-1.022-.377L8.711 7.158c-.17-.367.005-.8.4-.965M4.105 7.601a1.196 1.196 0 0 1 .664-1.61a1.32 1.32 0 0 1 1.7.626l4.647 10.024a1.19 1.19 0 0 1-.252 1.349a1.2 1.2 0 0 1-.407.261a1.32 1.32 0 0 1-1.705-.626L4.106 7.596zm.871-1.163A.79.79 0 0 1 6 6.815l4.647 10.024c.17.367-.005.8-.4.965c-.391.165-.848-.005-1.017-.377L4.582 7.403c-.174-.372 0-.8.395-.965");
}

.y62nxg54e {
  stop-color: var(--svg-color--8b3bef, #8b3bef);
}

.zxclguriz {
  stop-color: var(--svg-color--72f6fd, #72f6fd);
}

</style>
