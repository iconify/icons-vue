<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="qzcjkrqqh"/><path class="g6upzccuj"/><path class="f12ryeb7k"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:mute-background" /></template>
<style>
.f12ryeb7k {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.4 18.933a1.6 1.6 0 1 0 0-3.2a1.6 1.6 0 0 0 0 3.2");
}

.ft5dv1b6b {
  fill: none;
}

.g6upzccuj {
  fill: var(--svg-color--fff, #fff);
  d: path("M4 5.066h4.283l3.632 8.534h.17l3.627-8.534H20v9.6h-3.2v-4.25l-3.723 8.517h-2.154L7.2 10.368v8.565H4z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.qzcjkrqqh {
  fill: var(--svg-color--232843, #232843);
  d: path("M24 0H0v24h24z");
}

</style>
