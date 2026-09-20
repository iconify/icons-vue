<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGkaUitexT)" class="r4i437pya"/><path clip-rule="evenodd" class="m0h4xhbro"/></g><defs><linearGradient id="SVGkaUitexT" x1="12" x2="12" y1="4.686" y2="19.408" gradientUnits="userSpaceOnUse"><stop class="rmgchxbgh"/><stop offset="1" class="zhj5xobuz"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:skey-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.m0h4xhbro {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M5.13 15.172a3.71 3.71 0 0 1 0-5.33L9.273 5.79a3.92 3.92 0 0 1 5.452 0l4.145 4.051a3.71 3.71 0 0 1 0 5.331l-4.145 4.052l-.072.069l-.298-.933l3.533-3.415a3.12 3.12 0 0 0 0-4.519l-3.552-3.433c-1.29-1.248-3.383-1.248-4.674 0L6.11 10.426a3.12 3.12 0 0 0 0 4.518l3.542 3.425l-.284.945l-.095-.09zm8.89 2.14l3.034-3.034a2.253 2.253 0 0 0 0-3.186l-3.46-3.46a2.253 2.253 0 0 0-3.187 0l-3.461 3.46a2.253 2.253 0 0 0 0 3.186l3.027 3.028l.407-1.352l-2.566-2.565a1.317 1.317 0 0 1 0-1.864l3.254-3.254a1.316 1.316 0 0 1 1.864 0l3.253 3.254a1.32 1.32 0 0 1 0 1.864l-2.59 2.591zm-.748-2.337l1.947-1.96a.72.72 0 0 0 0-1.017l-2.713-2.731a.71.71 0 0 0-1.012 0l-2.713 2.73a.723.723 0 0 0 0 1.018l1.906 1.918l.289-.961a1.828 1.828 0 1 1 1.988.039z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.rmgchxbgh {
  stop-color: var(--svg-color--530491, #530491);
}

.zhj5xobuz {
  stop-color: var(--svg-color--03f3fb, #03f3fb);
}

</style>
