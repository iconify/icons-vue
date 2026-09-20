<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="om-y_pbvv"/><path class="m_jo28vao"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:nxt-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.m_jo28vao {
  fill: var(--svg-color--fff, #fff);
  d: path("M4 13.167a.5.5 0 0 1 .5-.5h1.667a.5.5 0 0 1 0 1H4.5a.5.5 0 0 1-.5-.5m10.667-2.333a.5.5 0 0 1 .5-.5H19.5a.5.5 0 0 1 .5.5v1.302a.5.5 0 1 1-1 0v-.803h-3.833a.5.5 0 0 1-.5-.5M4 10.834a.5.5 0 0 1 .5-.5h1.667c.093 0 .185.026.264.075l3.627 2.258h1.451a.5.5 0 0 1 0 1H9.915a.5.5 0 0 1-.264-.076l-3.628-2.258H4.5a.5.5 0 0 1-.5-.5m5.333 0a.5.5 0 0 1 .5-.5h1.824q.131 0 .247.065l3.985 2.268H17.5a.5.5 0 0 1 0 1h-1.743a.5.5 0 0 1-.248-.066l-3.985-2.268h-1.69a.5.5 0 0 1-.5-.5");
}

.om-y_pbvv {
  fill: var(--svg-color--008fbb, #008fbb);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
