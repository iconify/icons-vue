<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVG7KWeHdsZ)" class="r4i437pya"/><path clip-rule="evenodd" class="m4m2-2tpd"/></g><defs><linearGradient id="SVG7KWeHdsZ" x1="4.999" x2="18.998" y1="12.001" y2="13.5" gradientUnits="userSpaceOnUse"><stop class="g-on1_77v"/><stop offset=".64" class="o3_u8h_cq"/><stop offset="1" class="cu0931b5c"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:ooks-background" /></template>
<style>
.cu0931b5c {
  stop-color: var(--svg-color--c91819, #c91819);
}

.ft5dv1b6b {
  fill: none;
}

.g-on1_77v {
  stop-color: var(--svg-color--0a3b65, #0a3b65);
}

.m4m2-2tpd {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M14.748 4.001h-9.75v12.85L8.149 20h8.1a3.04 3.04 0 0 0 1.71-.55a2.56 2.56 0 0 0 1.04-2.2v-9c0-.194-.04-.49-.18-.744a.9.9 0 0 0-.82-.505h-.5v-.25c0-.48-.205-.805-.48-1a1.37 1.37 0 0 0-.77-.25h-.25v-.25c0-.205-.06-.51-.25-.77a1.18 1.18 0 0 0-1-.48m2.75 12V7.5h.5c.184 0 .3.095.38.245c.084.16.12.365.12.505v9c0 .92-.375 1.469-.835 1.8c-.47.334-1.04.449-1.415.449h-7.9l-1-1h7.15c1.16 0 1.92-.4 2.39-.93a2.46 2.46 0 0 0 .61-1.57m-3 2h-7.65l-1-1h8.4c.29 0 .72-.086 1.085-.35a1.64 1.64 0 0 0 .665-1.4V6h.25a.9.9 0 0 1 .48.15c.145.105.27.28.27.6V16c0 .324-.12.824-.49 1.24c-.355.41-.97.76-2.01.76m-9-13.5v12h8.75c.21 0 .53-.066.79-.25c.25-.18.46-.48.46-1v-10a.9.9 0 0 0-.15-.48c-.105-.145-.28-.27-.6-.27zm1 5.5c-.4 2.4 1.335 4 2.25 4.5l-.5.75c.085.084.55.25 1.75.25c1.5 0 4.25-1 4.5-4.5c.2-2.8-1.415-4-2.25-4.25l.75-1.25h-1.5c-1.75 0-4.5 1.5-5 4.5m2.5-.5c.6-1 1.75-.75 2.25-.5l.25-1c.75.5 1 1.25 1 2.5s-1.11 2-2 2c-.5 0-.835-.335-1-.5v1.25c-.75-.5-1.25-2.5-.5-3.75");
}

.o3_u8h_cq {
  stop-color: var(--svg-color--bc1b1f, #bc1b1f);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

</style>
