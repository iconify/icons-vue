<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="beaf9ac8r"/><path class="wq38yjbar"/><path class="nl1bstxho"/><path class="bxvuyrkug"/><path class="wnjj2of9p"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:polk-background" /></template>
<style>
.beaf9ac8r {
  fill: var(--svg-color--fff, #fff);
  d: path("M24 0H0v24h24z");
}

.bxvuyrkug {
  fill: var(--svg-color--51a0fc, #51a0fc);
  d: path("m18.737 12l-4.94-2.222L12 4z");
}

.ft5dv1b6b {
  fill: none;
}

.nl1bstxho {
  fill: var(--svg-color--3033be, #3033be);
  d: path("m12 20l-6.737-8l8.534-2.222z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.wnjj2of9p {
  fill: var(--svg-color--5751fb, #5751fb);
  d: path("m12 4l-6.737 8l8.535-2.222z");
}

.wq38yjbar {
  fill: var(--svg-color--5751fb, #5751fb);
  d: path("M18.737 12L12 20l1.797-10.222z");
}

</style>
