<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGdr2kObhR)" class="r4i437pya"/><path clip-rule="evenodd" class="q8hhzdf2g"/></g><defs><linearGradient id="SVGdr2kObhR" x1="5.588" x2="18.215" y1="8.376" y2="17.673" gradientUnits="userSpaceOnUse"><stop offset=".058" class="kucuuvb3c"/><stop offset=".306" class="xxyb1jwcz"/><stop offset=".819" class="pdtx7rblb"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:rari-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.kucuuvb3c {
  stop-color: var(--svg-color--2568ff, #2568ff);
}

.pdtx7rblb {
  stop-color: var(--svg-color--ff74f2, #ff74f2);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.q8hhzdf2g {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M4 6h12.79C18.564 6 20 7.427 20 9.187a3.19 3.19 0 0 1-1.78 2.855a3.14 3.14 0 0 1 1.767 3.1H20V18h-4.571v-3.043c0-.528-.485-.957-1.082-.957H8.57v4H4zm10.571 2.857h-6v1.714h6c.369 0 .858-.384.858-.857s-.489-.857-.858-.857");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.xxyb1jwcz {
  stop-color: var(--svg-color--5e9afe, #5e9afe);
}

</style>
