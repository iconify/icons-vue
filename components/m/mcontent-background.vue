<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVG9dgdHdoe)" class="r4i437pya"/><path clip-rule="evenodd" class="agfo5ackg"/></g><defs><linearGradient id="SVG9dgdHdoe" x1="12" x2="12" y1="4" y2="20" gradientUnits="userSpaceOnUse"><stop offset=".16" class="pgpna5u4g"/><stop offset="1" class="q-dngcn0x"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:mcontent-background" /></template>
<style>
.agfo5ackg {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("m11.966 20l-6.703-4.004V8.008L11.966 4l6.771 4.008V16zm1.09-14.51L8.982 7.976l2.94 1.734l4.058-2.442zm-6.109 7.676V9.095l1.55-.88l2.905 1.756l-1.507.884v3.932zm0 2.998v-2.5l2.948 1.772v2.484zm5.895-3.646v6.008l.842-.61v-4.758l1.264-.758v4.905l.842-.61v-4.813l1.263-.766v5.048l.842-.631V9.46zm-4.766-5.49l.623-.417l.56.467l-.627.413zm5.246 2.429l-.623.412l.556.464l.623-.413zM9.676 6.072l.623-.413l.556.463l-.623.417l-.556-.463zm5.242 2.43l-.623.412l.556.467l.623-.413l-.556-.463zm-3.65-3.374l.623-.412l.555.463l-.623.417zm5.241 2.43l-.623.413l.556.463l.623-.409l-.556-.463zm-9.995.391l.627-.412l.556.463l-.628.417l-.555-.463zm-.83 1.205l.842.417v.74l-.842-.42zm0 1.878l.842.412v.741l-.842-.42zm.842 2.29l-.842-.417v.737l.842.421zm-.842 1.461l.842.413v.74l-.842-.42zm5.474-2.619l-.842-.42v.74l.842.421zm0 1.874l-.842-.417v.737l.842.421zm-.842 1.461l.842.417v.74l-.842-.42v-.741zm.842 2.29l-.842-.416v.736l.842.422zm.602-7.41l-.623.417l.556.463l.623-.413l-.556-.463z");
}

.ft5dv1b6b {
  fill: none;
}

.pgpna5u4g {
  stop-color: var(--svg-color--c09124, #c09124);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.q-dngcn0x {
  stop-color: var(--svg-color--fddc03, #fddc03);
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

</style>
