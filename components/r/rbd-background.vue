<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="mumfproca"/><path class="vpn1ssvwi"/><path class="mkqk3tbwd"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:rbd-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.mkqk3tbwd {
  fill: var(--svg-color--fff, #fff);
  d: path("M4 4h12.294C17.974 4 20 4.901 20 6.848v2.79c0 .938-.523 1.765-1.28 2.287c1.003.48 1.28 1.616 1.28 2.224v3.003C20 19.056 17.44 20 15.867 20h-1.003l-2.912-4.368l.454-.038c1.706-.138 2.33-2.144 2.33-3.594c0-1.872-1.024-4.267-3.168-4.267H4zm.54.539v2.66h7.034c2.448 0 3.706 2.63 3.706 4.806c0 1.584-.661 3.637-2.39 4.064l2.268 3.397h.714c1.259 0 3.595-.736 3.595-2.31v-3.002c0-.896-.555-1.76-1.483-1.882l-.064-.518c.864-.325 1.547-1.173 1.547-2.111v-2.79c0-1.637-1.798-2.309-3.168-2.309H4.539z");
}

.mumfproca {
  fill: var(--svg-color--000, #000);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.vpn1ssvwi {
  fill: var(--svg-color--fff, #fff);
  d: path("M4 20v-3.733h5.051L11.467 20zm0-9.6v3.2h6.736c.427 0 1.264-.266 1.264-1.6c0-1.333-.842-1.6-1.264-1.6z");
}

</style>
