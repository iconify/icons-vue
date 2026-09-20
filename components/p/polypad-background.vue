<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGyRreMejH)" class="r4i437pya"/><path class="w7o_2abcq"/><path class="n1q9e_ght"/><path class="pppjucc_h"/><path class="uj6d1e-sb"/></g><defs><linearGradient id="SVGyRreMejH" x1="15.529" x2="8.668" y1="6" y2="18.108" gradientUnits="userSpaceOnUse"><stop class="uxp5lwzfo"/><stop offset="1" class="l6v58otxm"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:polypad-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.l6v58otxm {
  stop-color: var(--svg-color--a873ff, #a873ff);
}

.n1q9e_ght {
  fill: var(--svg-color--fff, #fff);
  d: path("M15.294 10.15L12 8.302l-3.294 1.85v8l1.882 1.016v-7.986L12 10.358l1.411.823v1.638L12 13.642v2.048l3.294-1.84z");
}

.pppjucc_h {
  fill: var(--svg-color--fff, #fff);
  d: path("M19.059 7.995L12 4L4.941 7.995l2.344 1.337L12 6.649l4.715 2.683z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.uj6d1e-sb {
  fill: var(--svg-color--fff, #fff);
  d: path("m12 8.301l-3.266 1.85l1.817 1.03l1.45-.828l1.449.824l1.844-1.026z");
}

.uxp5lwzfo {
  stop-color: var(--svg-color--4e4aff, #4e4aff);
}

.w7o_2abcq {
  fill: var(--svg-color--fff, #fff);
  d: path("M19.059 15.995v-8L12 4L4.941 7.995v8l2.353 1.323V9.332L12 6.649l4.706 2.683v5.336L12 17.341V20z");
}

</style>
