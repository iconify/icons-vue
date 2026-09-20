<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGkPOo0cIp)" class="r4i437pya"/><path class="xtw8adcqm"/></g><defs><linearGradient id="SVGkPOo0cIp" x1="4" x2="20" y1="12" y2="12" gradientUnits="userSpaceOnUse"><stop class="qax6shahd"/><stop offset="1" class="f73b25bzy"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:mwc-background" /></template>
<style>
.f73b25bzy {
  stop-color: var(--svg-color--9a00e6, #9a00e6);
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.qax6shahd {
  stop-color: var(--svg-color--3b00ca, #3b00ca);
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.xtw8adcqm {
  fill: var(--svg-color--fff, #fff);
  d: path("M16.563 8.162q2.281 2.268 3.195 3.199a.87.87 0 0 1 .24.583a.98.98 0 0 1-.308.784q-1.418 1.41-2.896 2.907c-.383.388-.831.484-1.32.2a4 4 0 0 1-.207-.184l-2.547-2.559q-.593-.598-1.252-.152c-.176.12-.352.328-.52.488q-1.105 1.102-2.2 2.215q-.285.294-.58.336c-.551.08-.787-.172-1.147-.535c-.896-.916-1.8-1.82-2.703-2.72a.97.97 0 0 1-.312-.612c-.04-.412.128-.651.416-.94l2.911-2.915c.056-.055.132-.095.2-.143c.532-.252.908-.056 1.3.34a275 275 0 0 0 2.51 2.523a.96.96 0 0 0 1.352-.036L15.3 8.32q.546-.541 1.26-.16z");
}

</style>
