<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="c5ue60bjn"/><path class="vh-7m5v9f"/><path clip-rule="evenodd" class="hdk0qwbsf"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:ronin-background" /></template>
<style>
.c5ue60bjn {
  fill: var(--svg-color--004de5, #004de5);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.hdk0qwbsf {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M6.286 15.102V5.23c0-.327.13-.64.362-.87S7.193 4 7.52 4h8.958a1.23 1.23 0 0 1 1.236 1.23v9.872a1.23 1.23 0 0 1-.464.96l-4.672 3.735a.93.93 0 0 1-1.158 0l-4.672-3.735a1.23 1.23 0 0 1-.463-.96m9.045-7.55v2.151c0 .285-.112.559-.311.76c-.2.202-.47.316-.753.316c.283 0 .554.113.754.315s.312.475.312.76v1.94a1.08 1.08 0 0 1-.4.84l-1.65 1.336a.133.133 0 0 1-.216-.105v-3.741a.8.8 0 0 0-.235-.57a.8.8 0 0 0-.565-.237h-1.2a.133.133 0 0 0-.133.134v4.414a.14.14 0 0 1-.076.122a.13.13 0 0 1-.141-.017l-1.65-1.337a1.07 1.07 0 0 1-.4-.839V7.552c0-.285.112-.559.312-.76c.2-.202.471-.316.754-.316h4.532c.283 0 .554.114.754.315c.2.202.312.476.312.76");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.vh-7m5v9f {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.066 10.24h1.2a.8.8 0 0 0 .565-.236a.8.8 0 0 0 .234-.57V7.686a.135.135 0 0 0-.133-.134h-1.866a.135.135 0 0 0-.133.134v2.42a.135.135 0 0 0 .133.135");
}

</style>
