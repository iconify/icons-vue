<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="m2cljwu5m"/><path class="iykn8jbdj"/><path class="rfkl-_ytm"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:pai-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.iykn8jbdj {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.784 8.324a3.027 3.027 0 1 0 0 6.053a3.027 3.027 0 0 0 0-6.053M7.459 11.35a4.324 4.324 0 1 1 8.649 0a4.324 4.324 0 0 1-8.649 0");
}

.m2cljwu5m {
  fill: var(--svg-color--10c7ca, #10c7ca);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.rfkl-_ytm {
  fill: var(--svg-color--fff, #fff);
  d: path("M8.108 10.703a.65.65 0 0 1 .649.649v8a.649.649 0 0 1-1.298 0v-8a.65.65 0 0 1 .65-.649m7.351 0a.65.65 0 0 1 .649.649v4.108a.648.648 0 1 1-1.297 0v-4.108a.65.65 0 0 1 .648-.649m-.001-4.541a1.081 1.081 0 1 0 0-2.162a1.081 1.081 0 0 0 0 2.162");
}

</style>
