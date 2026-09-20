<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="qcg-37yuf"/><path class="n_44bi6cq"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:moonbase-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.n_44bi6cq {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.629 16.066c.002-.358 1.37-.343 1.36-.678c-.006-.258-.612-.252-.422-.798c.28-.815.433-1.689.433-2.598C20 7.578 16.418 4 12 4s-8 3.578-8 7.992c0 .912.153 1.788.436 2.605l.017.05c.114.362-.451.505-.451.72c0 .34 1.19.294 1.19.689c0 .343-1.177.449-1.177.796c0 .478 2.606.311 2.64.723c.025.318-.897.337-.902.677c-.009.541 3.557.364 3.557.725c0 .272-1.622.174-1.622.496c0 .323 2.135.527 4.487.527s3.976-.261 3.976-.544s-1.514-.224-1.483-.48c.055-.444 3.416-.217 3.416-.731c0-.272-.925-.335-.895-.627c.043-.414 2.811-.352 2.811-.78c0-.338-1.371-.421-1.37-.771zm-2.145-1.038c-.074.272.769.313.769.598c0 .346-2.57.208-2.544.666c.016.29 1.826.338 1.791.64c-.05.436-2.803.218-2.83.636c-.02.306 1.344.317 1.347.596c.002.236-1.072.364-3.127.364c-2.342 0-3.48-.126-3.35-.389c.12-.246 2.194-.2 2.173-.586s-3.682-.272-3.792-.646c-.092-.311 1.202-.375 1.194-.67c-.008-.302-1.658-.234-1.694-.598c-.024-.24.862-.224.823-.525c-.027-.22-.393-.189-.61-.64a5.907 5.907 0 0 1 5.364-8.385a5.907 5.907 0 0 1 5.457 8.172c-.278.629-.903.502-.973.767z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.qcg-37yuf {
  fill: var(--svg-color--2b1d3c, #2b1d3c);
  d: path("M24 0H0v24h24z");
}

</style>
