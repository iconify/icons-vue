<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGggbxYd5s)" class="r4i437pya"/><path class="yhiltsbig"/></g><defs><linearGradient id="SVGggbxYd5s" x1="10.909" x2="13.721" y1="7.302" y2="19.387" gradientUnits="userSpaceOnUse"><stop offset=".18" class="wvxzetb7r"/><stop offset=".23" class="po-x6pbfy"/><stop offset=".31" class="aucn-8m7b"/><stop offset=".4" class="q-_-sxlgr"/><stop offset=".51" class="sivfzgbzu"/><stop offset=".62" class="qjxt69obc"/><stop offset=".74" class="o_swsjoqm"/><stop offset=".78" class="wli72ud7c"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:thundercore-background" /></template>
<style>
.aucn-8m7b {
  stop-color: var(--svg-color--00e4d5, #00e4d5);
}

.ft5dv1b6b {
  fill: none;
}

.o_swsjoqm {
  stop-color: var(--svg-color--0016d5, #0016d5);
}

.po-x6pbfy {
  stop-color: var(--svg-color--00f8d5, #00f8d5);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.q-_-sxlgr {
  stop-color: var(--svg-color--00c3d5, #00c3d5);
}

.qjxt69obc {
  stop-color: var(--svg-color--005cd5, #005cd5);
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.sivfzgbzu {
  stop-color: var(--svg-color--0096d5, #0096d5);
}

.wli72ud7c {
  stop-color: var(--svg-color--0000d5, #0000d5);
}

.wvxzetb7r {
  stop-color: var(--svg-color--00ffd5, #00ffd5);
}

.yhiltsbig {
  fill: var(--svg-color--fff, #fff);
  d: path("M7.343 11.514a.355.355 0 0 0 .3.544h4.052a.17.17 0 0 1 .145.26l-3.977 6.368a.14.14 0 0 1-.2.045a8.009 8.009 0 0 1 4.081-14.73a.14.14 0 0 1 .122.215zm9.139-6.144a.14.14 0 0 0-.2.043l-3.917 6.274a.17.17 0 0 0 .144.26h4.053a.354.354 0 0 1 .3.544l-4.582 7.337a.11.11 0 0 0 .042.158q.027.015.058.013a8.007 8.007 0 0 0 4.1-14.63z");
}

</style>
