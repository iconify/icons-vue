<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="ctnkkxx2y"/><path class="jymbxhi8z"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:near-background" /></template>
<style>
.ctnkkxx2y {
  fill: var(--svg-color--00ec97, #00ec97);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.jymbxhi8z {
  fill: var(--svg-color--fff, #fff);
  d: path("m16.823 4.817l-3.343 4.96c-.229.343.217.743.537.463l2.914-2.857c.086-.074.212-.023.212.103v8.943c0 .12-.16.171-.229.085L7.337 4.606A1.64 1.64 0 0 0 6.04 4C5.011 4 4 4.52 4 5.71v12.577a1.709 1.709 0 0 0 3.16.891l3.337-4.96c.229-.343-.211-.743-.531-.463L7.069 16.67c-.086.074-.212.023-.212-.103v-8.92c0-.126.16-.172.229-.086l9.56 11.834c.32.395.8.606 1.297.606C18.977 20 20 19.486 20 18.291V5.714a1.714 1.714 0 0 0-3.177-.891z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
