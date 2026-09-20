<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="id3sd59wh"/><path class="rljbkcbnx"/><path clip-rule="evenodd" class="gwbt7fbya"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:tips-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.gwbt7fbya {
  fill: var(--svg-color--000, #000);
  fill-rule: evenodd;
  d: path("M8.209 8.5c0 .28.358.59.882.59c.325 0 1.26-.484 2.327-1.032c1.508-.776 3.273-1.687 3.889-1.522c.174.28.582 1.454.79 2.802l.16.068C17.479 9.9 20 10.928 20 12c0 1.401-3.903 6.303-9.687 6.303C4.523 18.303 4 14.38 4 13.542c0-.844 1.052-2.803 3.947-3.928c.174-.087.262-.669.262-1.115m-.815 3.015c.174.465.95 1.454 2.424 1.454c1.843 0 5.78-2.346 6.303-2.908v2.181c0 .63-3.975 2.91-5.818 2.91s-3.151-1.33-3.151-1.892c0-.446.155-1.372.242-1.745");
}

.id3sd59wh {
  fill: var(--svg-color--f7c91e, #f7c91e);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.rljbkcbnx {
  fill: var(--svg-color--000, #000);
  d: path("M8.994 8.78c-.63 0-.785-.562-.785-.843c.175-.654.824-2.24 2.104-2.24c1.843 0 3.787.204 4.839.485c-2.366.563-5.367 2.599-6.158 2.599");
}

</style>
