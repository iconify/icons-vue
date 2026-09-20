<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGt6CtBbxE)" class="r4i437pya"/><path class="aa5cw6mmv"/></g><defs><linearGradient id="SVGt6CtBbxE" x1="3.948" x2="19.217" y1="16.617" y2="7.645" gradientUnits="userSpaceOnUse"><stop class="lajobnbva"/><stop offset=".88" class="i1_812bwr"/><stop offset="1" class="qdp6cac7z"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:polygon-zkevm-background" /></template>
<style>
.aa5cw6mmv {
  fill: var(--svg-color--fff, #fff);
  d: path("m15.88 14.86l3.794-2.165a.64.64 0 0 0 .326-.558v-4.33a.64.64 0 0 0-.326-.556L15.88 5.086a.66.66 0 0 0-.65 0L11.432 7.25a.64.64 0 0 0-.325.557v7.737l-2.662 1.517l-2.661-1.517v-3.036l2.661-1.517l1.755 1.001V9.958l-1.43-.816a.66.66 0 0 0-.65 0l-3.796 2.165a.64.64 0 0 0-.325.557v4.33c0 .229.124.442.325.557l3.796 2.165c.2.114.45.114.65 0l3.796-2.165a.64.64 0 0 0 .325-.557V8.455l.048-.026l2.613-1.49l2.661 1.516v3.036l-2.661 1.517l-1.753-.999v2.037l1.427.814a.66.66 0 0 0 .651 0z");
}

.ft5dv1b6b {
  fill: none;
}

.i1_812bwr {
  stop-color: var(--svg-color--803bdf, #803bdf);
}

.lajobnbva {
  stop-color: var(--svg-color--a726c1, #a726c1);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.qdp6cac7z {
  stop-color: var(--svg-color--7b3fe4, #7b3fe4);
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

</style>
