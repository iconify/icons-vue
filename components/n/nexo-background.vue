<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="beaf9ac8r"/><path class="ok4ohpbdi"/><path class="a2z1xy76y"/><path class="dm17jzaof"/><path class="brua03b0m"/><path class="ifxargpmz"/><path class="c6r0n3b_r"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:nexo-background" /></template>
<style>
.a2z1xy76y {
  fill: var(--svg-color--2853c3, #2853c3);
  d: path("m15.995 5.244l-3.998 2.25l3.998 2.25z");
}

.beaf9ac8r {
  fill: var(--svg-color--fff, #fff);
  d: path("M24 0H0v24h24z");
}

.brua03b0m {
  fill: var(--svg-color--2853c3, #2853c3);
  d: path("m20 16.497l-3.85 2.163a.33.33 0 0 1-.326 0l-7.838-4.41V9.737z");
}

.c6r0n3b_r {
  fill: var(--svg-color--3ca9e5, #3ca9e5);
  d: path("m7.999 18.75l3.999-2.25l-3.999-2.256z");
}

.dm17jzaof {
  fill: var(--svg-color--1a4199, #1a4199);
  d: path("m15.995 5.244l3.845 2.16a.31.31 0 0 1 .153.264v8.826l-3.998-2.244z");
}

.ft5dv1b6b {
  fill: none;
}

.ifxargpmz {
  fill: var(--svg-color--60beff, #60beff);
  d: path("M4 7.494v8.826a.31.31 0 0 0 .154.276l3.844 2.16V9.745z");
}

.ok4ohpbdi {
  fill: var(--svg-color--3ca9e5, #3ca9e5);
  d: path("m8.152 5.336l7.837 4.41v4.5L4 7.5l3.844-2.16a.33.33 0 0 1 .308 0z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
