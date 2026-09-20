<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="ctnkkxx2y"/><path class="e22pggblb"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:near-protocol-background" /></template>
<style>
.ctnkkxx2y {
  fill: var(--svg-color--00ec97, #00ec97);
  d: path("M24 0H0v24h24z");
}

.e22pggblb {
  fill: var(--svg-color--000, #000);
  d: path("m16.823 4.818l-3.343 4.96c-.228.342.217.742.537.462l2.915-2.857c.085-.074.21-.023.21.102v8.944c0 .12-.16.171-.227.086L7.337 4.605A1.64 1.64 0 0 0 6.04 4C5.012 4 4 4.52 4 5.71v12.575a1.708 1.708 0 0 0 3.16.892l3.337-4.96c.228-.342-.212-.742-.532-.462l-2.897 2.914c-.085.074-.21.023-.21-.104v-8.92c0-.125.16-.17.227-.085l9.56 11.835c.32.394.8.605 1.297.605C18.978 20 20 19.485 20 18.292V5.715a1.715 1.715 0 0 0-3.177-.892z");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
