<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="p9tqkhbiw"/><path class="m56mc42nz"/><path class="uu00vobcb"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:prob-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.m56mc42nz {
  fill: var(--svg-color--fff, #fff);
  d: path("m13.68 8.644l-1.333-.756a.9.9 0 0 0-.8 0l-1.338.756c-.289.164-.289.43 0 .595l1.333.77a.9.9 0 0 0 .8 0l1.333-.77c.29-.164.29-.43 0-.595z");
}

.p9tqkhbiw {
  fill: var(--svg-color--4231c8, #4231c8);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.uu00vobcb {
  fill: var(--svg-color--fff, #fff);
  d: path("m18.71 7.707l-6.315-3.613a.88.88 0 0 0-.79 0l-6.32 3.613a.86.86 0 0 0-.396.68v7.227a.87.87 0 0 0 .396.68l6.32 3.613a.88.88 0 0 0 .79 0l6.32-3.614a.86.86 0 0 0 .396-.68V8.388a.87.87 0 0 0-.396-.68zm-2.812 1.68l-3.6 2.102a.84.84 0 0 1-.782 0l-2.143-1.4c-.284-.164-.488-.03-.488.294v4.03c0 .32-.263.463-.547.312l-.387-.205a.83.83 0 0 1-.4-.666V9.467c0-.249.17-.551.387-.675l3.578-2.08a.87.87 0 0 1 .786 0l3.596 2.08c.284.16.284.43 0 .595");
}

</style>
