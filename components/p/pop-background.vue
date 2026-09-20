<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGSKMsDbSi)" class="r4i437pya"/><path class="nqjlw1bfs"/></g><defs><linearGradient id="SVGSKMsDbSi" x1="12.4" x2="10" y1="8" y2="15.2" gradientUnits="userSpaceOnUse"><stop class="qgzh5bb9g"/><stop offset=".12" class="rs-3iws3g"/><stop offset=".18" class="zjgk99b-g"/><stop offset=".24" class="ofl_-xb-p"/><stop offset=".3" class="qw_2y6x-p"/><stop offset=".37" class="wwasz5mot"/><stop offset=".45" class="om3e9bb_q"/><stop offset=".56" class="uwt5ebpbf"/><stop offset=".75" class="m-0ofacqa"/><stop offset=".91" class="u4xt3wbvr"/><stop offset="1" class="ji69y85_l"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:pop-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.ji69y85_l {
  stop-color: var(--svg-color--c379ad, #c379ad);
}

.m-0ofacqa {
  stop-color: var(--svg-color--7443b7, #7443b7);
}

.nqjlw1bfs {
  fill: var(--svg-color--fff, #fff);
  d: path("M6.8 13.6H18V8.8h2v6.4H6.8zM6 15.2H4V8.8h13.2v1.6H6zm11.2-2.4v-1.6H6.8v1.6z");
}

.ofl_-xb-p {
  stop-color: var(--svg-color--cc83a1, #cc83a1);
}

.om3e9bb_q {
  stop-color: var(--svg-color--8851b7, #8851b7);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.qgzh5bb9g {
  stop-color: var(--svg-color--00bac9, #00bac9);
}

.qw_2y6x-p {
  stop-color: var(--svg-color--663fa9, #663fa9);
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.rs-3iws3g {
  stop-color: var(--svg-color--2060b2, #2060b2);
}

.u4xt3wbvr {
  stop-color: var(--svg-color--8f48a9, #8f48a9);
}

.uwt5ebpbf {
  stop-color: var(--svg-color--e096ac, #e096ac);
}

.wwasz5mot {
  stop-color: var(--svg-color--3557b8, #3557b8);
}

.zjgk99b-g {
  stop-color: var(--svg-color--7046b2, #7046b2);
}

</style>
