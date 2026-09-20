<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="sw8lrx8vn"/><path class="d4c-alb1u"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:pip-background" /></template>
<style>
.d4c-alb1u {
  fill: var(--svg-color--fff, #fff);
  d: path("M7.015 8.11A2.91 2.91 0 0 0 4 11.105v4.69c0 .087.009.096.091.096H5.64c.078 0 .09-.009.09-.095v-1.635h1.224c1.86 0 3.1-1.331 3.1-3.035a2.94 2.94 0 0 0-3.04-3.018m0 1.729c.826 0 1.31.562 1.31 1.306c0 .739-.484 1.288-1.358 1.288H5.731v-1.297c0-.73.45-1.297 1.288-1.297zm9.944-1.73a2.91 2.91 0 0 0-3.013 2.997v4.69c0 .087.008.096.09.096h1.548c.078 0 .091-.009.091-.095V14.16H16.9c1.86 0 3.1-1.331 3.1-3.035a2.94 2.94 0 0 0-3.04-3.018m0 1.73c.826 0 1.31.562 1.31 1.306c0 .739-.484 1.288-1.357 1.288h-1.237v-1.297c0-.73.45-1.297 1.289-1.297zm-5.945.432c-.052 0-.095.035-.095.078v3.736c0 .043.043.077.095.077h1.54c.051 0 .095-.034.095-.077v-3.736c0-.043-.044-.078-.095-.078zm-.095-1.297a.865.865 0 1 1 1.73 0a.865.865 0 0 1-1.73 0");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.sw8lrx8vn {
  fill: var(--svg-color--073de8, #073de8);
  d: path("M24 0H0v24h24z");
}

</style>
