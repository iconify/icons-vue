<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGYyN0Bbbd)" class="r4i437pya"/><path clip-rule="evenodd" class="cpn8lyfiw"/></g><defs><linearGradient id="SVGYyN0Bbbd" x1="5.398" x2="18.457" y1="10.906" y2="10.906" gradientUnits="userSpaceOnUse"><stop class="rlqg8eblf"/><stop offset=".495" class="on13jubrr"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:rfox-background" /></template>
<style>
.cpn8lyfiw {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M5.29 10.56V4l3.252 3.355zm9.105-2.431H9.616l2.435 10.198zm-5.461.03L11.819 20l-6.026-8.765zm6.133 0L12.18 20l6.026-8.765zm3.643 2.4V4l-3.252 3.355z");
}

.ft5dv1b6b {
  fill: none;
}

.on13jubrr {
  stop-color: var(--svg-color--ed1c24, #ed1c24);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.rlqg8eblf {
  stop-color: var(--svg-color--af0607, #af0607);
}

</style>
