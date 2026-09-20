<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGOFdGVbMa)" class="r4i437pya"/><path clip-rule="evenodd" class="c36fwvb_i"/><path clip-rule="evenodd" class="vagnlmvhl"/></g><defs><linearGradient id="SVGOFdGVbMa" x1="18.018" x2="9.426" y1="7.26" y2="16.516" gradientUnits="userSpaceOnUse"><stop class="p5a2awbap"/><stop offset="1" class="dr75gcb5m"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:max-background" /></template>
<style>
.c36fwvb_i {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M12.842 17.245a2.855 2.855 0 0 1-3.997-.055l-4.05-4.13a2.804 2.804 0 0 1 .054-3.967a2.855 2.855 0 0 1 4 .054l4.051 4.131a2.78 2.78 0 0 1-.054 3.966zm-6.317-5.668a.842.842 0 1 0 0-1.684a.842.842 0 0 0 0 1.684m6.127 3.66c0 .837-.686 1.515-1.529 1.515a1.523 1.523 0 0 1-1.528-1.516c0-.838.686-1.516 1.528-1.516c.843 0 1.529.678 1.529 1.516");
}

.dr75gcb5m {
  stop-color: var(--svg-color--9cce7e, #9cce7e);
}

.ft5dv1b6b {
  fill: none;
}

.p5a2awbap {
  stop-color: var(--svg-color--0cb5ad, #0cb5ad);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.vagnlmvhl {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M9.152 17.47a3.38 3.38 0 0 1-.307-4.797l5.166-5.84a3.444 3.444 0 0 1 4.83-.303a3.38 3.38 0 0 1 .303 4.796l-5.162 5.84a3.444 3.444 0 0 1-4.83.303m1.97-.716c.843 0 1.53-.678 1.53-1.516s-.687-1.516-1.53-1.516c-.841 0-1.528.678-1.528 1.516s.687 1.516 1.529 1.516m7.193-7.496a1.895 1.895 0 1 1-3.791 0a1.895 1.895 0 0 1 3.79 0");
}

</style>
