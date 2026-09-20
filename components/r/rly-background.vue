<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGKUkQSkzN)" class="r4i437pya"/><path clip-rule="evenodd" class="em_2sd6-o"/></g><defs><linearGradient id="SVGKUkQSkzN" x1="12" x2="12" y1="4" y2="20" gradientUnits="userSpaceOnUse"><stop class="bjfsq2bqn"/><stop offset="1" class="q29knxr1g"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:rly-background" /></template>
<style>
.bjfsq2bqn {
  stop-color: var(--svg-color--ff4500, #ff4500);
}

.em_2sd6-o {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M19.059 8L12 4L4.941 8v8L12 20l7.059-4zm-2.355.941l-4.706-2.588L7.294 8.94v5.177l2.353 1.294v-4.985l2.352-1.25l2.35 1.248l2.356-1.467z");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.q29knxr1g {
  stop-color: var(--svg-color--ffc604, #ffc604);
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

</style>
