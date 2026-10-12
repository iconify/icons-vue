<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="pkcvu_bdw"/><path class="qpf3-4b8n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:stream" /></template>
<style>
.pkcvu_bdw {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.4 21.25c.44-.47 2.15-1.89 2.68-2.83c.54-.95.65-1.89.54-2.84c-.11-.94-.78-1.89-1.2-2.83S8.33 10.86 8.1 9.92c-.23-.95-.28-1.89-.04-2.84c.24-.94 1.23-2.36 1.48-2.83m8.36 17c.22-.47 1.26-1.89 1.35-2.83c.09-.95-.25-1.89-.8-2.84c-.55-.94-1.66-1.89-2.53-2.83c-.86-.94-1.98-1.89-2.66-2.83c-.67-.95-1.17-1.89-1.37-2.84c-.2-.94.13-2.36.15-2.83m1.8 15.64c.1-.16.44-.64.6-.96s.29-.65.36-.97s.1-.64.08-.96a3.6 3.6 0 0 0-.18-.96c-.1-.32-.24-.65-.41-.97s-.5-.8-.6-.96");
}

.qpf3-4b8n {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8.19 16.15h.01m8.22-5.44h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
