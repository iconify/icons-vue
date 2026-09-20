<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGIZpI8cdk)" class="r4i437pya"/><path clip-rule="evenodd" class="ez3-ovjzz"/></g><defs><linearGradient id="SVGIZpI8cdk" x1="12" x2="12" y1="6.996" y2="17.004" gradientUnits="userSpaceOnUse"><stop class="doc5tobgq"/><stop offset="1" class="g-o08bk5b"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:vext-background" /></template>
<style>
.doc5tobgq {
  stop-color: var(--svg-color--6564fe, #6564fe);
}

.ez3-ovjzz {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("m18.584 8.472l-4.567 4.688a.04.04 0 0 0-.012.028q-.002.014.007.028l.552.868l1.824 2.896c.012.02.008.028-.016.016l-2.96-1.44q-.599-.298-.891-.368a2.24 2.24 0 0 0-1.56.188l-3.328 1.62q-.06.025-.024-.028l.356-.552l2.032-3.212a.04.04 0 0 0-.004-.04L8.925 12.08l-4.9-5.04q-.059-.058.02-.04l7.372 2.12c.24.072.492.096.744.072q.241-.018.668-.144q3.582-1.02 7.163-2.047l.005.003l.003.005v.012l-1.416 1.447zm-5.86 1.68q2.287-.775 4.576-1.544q.018.002 0 .016l-4.771 2.972a.93.93 0 0 1-.7.14a2 2 0 0 1-.604-.288Q8.96 10.02 6.757 8.656q-.151-.09.016-.036l4.816 1.636c.24.08.44.112.66.052q.103-.029.476-.16zm4.8-1.42q-.001-.016-.032-.02a1278 1278 0 0 0-4.76 3.356q-.358.251-.547.292a.92.92 0 0 1-.736-.16q-2.506-1.77-5.016-3.536v.016l4.532 4.44a.04.04 0 0 1 .012.028a.04.04 0 0 1-.008.028l-2.572 3.012q-.089.108.02.024a441 441 0 0 0 3.044-2.232a.85.85 0 0 1 .712-.168q.199.041.536.292q1.462 1.08 2.935 2.148q.008 0 .004-.012l-.004-.008l-2.62-3.064l-.006-.01a.03.03 0 0 1 0-.02l.007-.01l4.495-4.392z");
}

.ft5dv1b6b {
  fill: none;
}

.g-o08bk5b {
  stop-color: var(--svg-color--4c40f8, #4c40f8);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

</style>
