<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="aym0yoqjh"/><path clip-rule="evenodd" class="jvvnneblr"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:pond-background" /></template>
<style>
.aym0yoqjh {
  fill: var(--svg-color--3840c7, #3840c7);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.jvvnneblr {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M14.347 6.982a1.1 1.1 0 0 0-.768-.316h-.003a1.08 1.08 0 0 0-.768.32l-8.49 8.498a1.08 1.08 0 0 0-.318.768c0 .289.115.56.32.765a1.08 1.08 0 0 0 .768.316c.292 0 .566-.113.772-.319l8.49-8.5a1.085 1.085 0 0 0-.003-1.532m4.978-.232a1.09 1.09 0 0 0-1.19.236l-8.519 8.498c-.204.204-.284.48-.283.768c0 .287.082.562.287.765a1.1 1.1 0 0 0 1.545-.004l6.613-6.635v5.87c0 .288.153.564.358.767a1.097 1.097 0 0 0 1.544 0a1.08 1.08 0 0 0 .32-.766V7.75a1.07 1.07 0 0 0-.675-1.002");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
