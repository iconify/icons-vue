<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="zf9yjiz2g"/><path class="b02m6q8ob"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:nvir-background" /></template>
<style>
.b02m6q8ob {
  fill: var(--svg-color--fff, #fff);
  d: path("M4 16h1.2v-3.672C5.2 10.92 6.4 9.6 7.8 9.6s2.6 1.324 2.6 2.728V14h1.2v-1.748c0-2.12-1.64-3.852-3.652-3.852h-.296C5.64 8.4 4 10.128 4 12.252zm6.4 0v-1.2h1.2V16zm.8-7.6h1.632l2.544 5.492c.032.064.1.108.164.108q.118.001.164-.1L17.6 10l1.4.6l-2.22 4.644a1.32 1.32 0 0 1-1.208.756a1.32 1.32 0 0 1-1.204-.756zm7.4-.4L18 9.2l1.4.6l.6-1.2z");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.zf9yjiz2g {
  fill: var(--svg-color--044aef, #044aef);
  d: path("M24 0H0v24h24z");
}

</style>
