<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="t0gggku-e"/><path class="bnx1-qbqx"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:mmpro-background" /></template>
<style>
.bnx1-qbqx {
  fill: var(--svg-color--fff, #fff);
  d: path("M15.429 9.333V7.43h-.381v1.904h-.743l-1.162 1.421V7.048h-.953V4h-.38v3.048h-.953v3.706l-1.162-1.42h-.743V7.428h-.38v1.904H7.81v5.334h.761v3.047h.381v-3.047h.762V11.63l1.143 1.333v3.226h.953V20h.38v-3.81h.953v-3.222l1.143-1.334v3.033h.762v3.047h.38v-3.047h.762V9.333z");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.t0gggku-e {
  fill: var(--svg-color--3c6, #3c6);
  d: path("M24 0H0v24h24z");
}

</style>
