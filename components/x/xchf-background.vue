<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="wra3drbfw"/><path class="o__gwfbpe"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:xchf-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.o__gwfbpe {
  fill: var(--svg-color--fff, #fff);
  d: path("m9.111 12.952l-.442-.722L6.336 16h1.413l5.734-9.333L20 17.334h-8.212l-1.37-2.242l.776-1.268L12.553 16h5.111l-4.18-6.794l-4.97 8.128H4l4.67-7.64l1.216 1.99z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.wra3drbfw {
  fill: var(--svg-color--ce0e2d, #ce0e2d);
  d: path("M24 0H0v24h24z");
}

</style>
