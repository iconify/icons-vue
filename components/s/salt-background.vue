<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGjrwyQebn)" class="r4i437pya"/><path class="mkoh4gmse"/></g><defs><linearGradient id="SVGjrwyQebn" x1="8.819" x2="19.724" y1="12" y2="20" gradientUnits="userSpaceOnUse"><stop class="qg0r_bc9v"/><stop offset="1" class="i102b6g5h"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:salt-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.i102b6g5h {
  stop-color: var(--svg-color--687883, #687883);
}

.mkoh4gmse {
  fill: var(--svg-color--fff, #fff);
  d: path("m12 8.911l4.414 8.882H7.588zM12 4L4.276 20h15.448z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.qg0r_bc9v {
  stop-color: var(--svg-color--17babc, #17babc);
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

</style>
