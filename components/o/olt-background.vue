<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="xe0xsw1oj"/><path class="ztjo2bb-h"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:olt-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.xe0xsw1oj {
  fill: var(--svg-color--008d9f, #008d9f);
  d: path("M24 0H0v24h24z");
}

.ztjo2bb-h {
  fill: var(--svg-color--fff, #fff);
  d: path("m8.25 4l3.247 1.875v3.75L8.25 11.5L5.002 9.625v-3.75zm0 8.5l3.247 1.875v3.75L8.25 20l-3.248-1.875v-3.75zm7.5-8.5l3.247 1.875v3.75L15.75 11.5l-3.248-1.875v-3.75zm0 8.5l3.247 1.875v3.75L15.749 20l-3.248-1.875v-3.75z");
}

</style>
