<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGyszp4dfe)" class="r4i437pya"/><path clip-rule="evenodd" class="bh6bogbrx"/></g><defs><linearGradient id="SVGyszp4dfe" x1="0" x2="24" y1="0" y2="24" gradientUnits="userSpaceOnUse"><stop class="uost1iwav"/><stop offset="1" class="c2kirvh2m"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:npro-background" /></template>
<style>
.bh6bogbrx {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("m10.63 4l-5.36 7.645l-.124.506l5.484 7.837l.153-.04l.009-.202l-3.807-6.098l-.238-.586l.339.085l1.227.726l2.722 4.402l.114-.15l-.203-.505l-1.658-3.343l-.076-.337l.203-.092l5.367.05l-.078.38l-1.795 3.645l-.067.304l.117.051l2.645-4.304l.19-.218l1.423-.694l-.044.304l-3.976 6.38l-.008.202l.175.052l5.366-7.644l.123-.508l-5.336-7.696l-.254-.144l-.09.144l.191.377l4.247 6.812l.114.304l-.062.203l-1.564.852l-.308.06l-2.407-5.47l-.425-.715l-.114.109l.08.405l1.805 5.062l.2.81l-5.818.011l-.014-.213l2.11-5.974l-.173-.21L8.25 12.76l-.352-.038l-1.479-.773l-.156-.201l.066-.304l4.468-7.19l.007-.202z");
}

.c2kirvh2m {
  stop-color: var(--svg-color--1bd6d5, #1bd6d5);
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.uost1iwav {
  stop-color: var(--svg-color--9498fe, #9498fe);
}

</style>
