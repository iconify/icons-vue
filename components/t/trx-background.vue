<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="jh-hgcbaa"/><path clip-rule="evenodd" class="gqauf7b7r"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:trx-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.gqauf7b7r {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M5.26 4.165a.5.5 0 0 1 .492-.15l10.581 2.59a.5.5 0 0 1 .177.082l2.153 1.57a.5.5 0 0 1 .118.687l-7.407 10.837a.5.5 0 0 1-.887-.115L5.161 4.67a.5.5 0 0 1 .1-.505m1.747 2.707l3.698 10.41l.608-5.395zm5.295 5.189l-.617 5.489l5.23-7.654zm5.085-3.494l-3.372 1.582l2.26-2.392zm-2.13-1.193L7.032 5.36l4.823 5.617z");
}

.jh-hgcbaa {
  fill: var(--svg-color--c4342b, #c4342b);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
