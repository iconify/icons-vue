<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGav2z1dND)" class="r4i437pya"/><path class="umsqyh2pz"/></g><defs><linearGradient id="SVGav2z1dND" x1="4" x2="13.08" y1="6.9" y2="15.775" gradientUnits="userSpaceOnUse"><stop class="v6jni79nq"/><stop offset=".89" class="hke-fq0-t"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:mbx-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.hke-fq0-t {
  stop-color: var(--svg-color--9600ff, #9600ff);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.umsqyh2pz {
  fill: var(--svg-color--fff, #fff);
  d: path("M4 18V6h3.195l4.73 4.61L16.66 6H20v12h-.3l-2.085-2.05l-3.59-3.325l.115-.1l3.36 3.11v-7.37l-5.575 5.075L6.5 8.265v7.37l3.36-3.11l.115.1L4.175 18h-.13l-.02-.02zm7.435-4.065l.115.1L7.27 18h-.22zm-.4-.36l.115.1L6.485 18H6.26zm-.38-.34l.115.1L5.735 18H5.51l5.15-4.765zm-.37-.33l.115.1L5.01 18h-.225zm2.28 1.03l-.115.1L16.73 18h.22zm.4-.36l-.115.1L17.515 18h.225zm.38-.34l-.115.1L18.265 18h.225l-5.15-4.765zm.37-.33l-.115.1L18.99 18h.225z");
}

.v6jni79nq {
  stop-color: var(--svg-color--4babff, #4babff);
}

</style>
