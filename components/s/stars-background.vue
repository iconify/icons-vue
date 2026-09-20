<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="icfg452kz"/><path class="hesy9zb9f"/><path class="lowl8jb3s"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:stars-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.hesy9zb9f {
  fill: var(--svg-color--fff, #fff);
  d: path("M8.961 10.21a.24.24 0 0 0-.259-.316l-4.493.64a.24.24 0 0 0-.142.405l3.2 3.303a.237.237 0 0 0 .336.012a.24.24 0 0 0 .064-.106zM7.33 19.46a.235.235 0 0 0 .333.283l4.202-1.995a.24.24 0 0 1 .198 0l4.39 1.99a.24.24 0 0 0 .325-.296c-.829-2.494-1.577-4.96-2.377-7.45a.235.235 0 0 0-.423-.046l-1.774 3.18a.24.24 0 0 1-.212.123h-.075a.24.24 0 0 1-.207-.127l-1.722-3.167a.24.24 0 0 0-.207-.127h-.024a.236.236 0 0 0-.23.17a217 217 0 0 0-2.198 7.462m8.971-5.383a.235.235 0 0 0 .396.094l3.232-3.232a.241.241 0 0 0-.136-.41l-4.47-.626a.24.24 0 0 0-.264.311z");
}

.icfg452kz {
  fill: var(--svg-color--e2bb5e, #e2bb5e);
  d: path("M24 0H0v24h24z");
}

.lowl8jb3s {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.799 9.824a.28.28 0 0 0 0-.222l-.024-.056l-1.585-5.138a.235.235 0 0 0-.457 0L10.18 9.546l-.023.075a.25.25 0 0 0 .01.179l1.538 3.548a.25.25 0 0 0 .216.141h.057a.24.24 0 0 0 .216-.141l1.6-3.525z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
