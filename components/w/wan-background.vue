<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="uub5b3bfk"/><path class="jclhwre0v"/><path class="ynwn50bfr"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:wan-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.jclhwre0v {
  fill: var(--svg-color--fff, #fff);
  d: path("m5.496 8.596l1.734.867v4.163L12 10.989l4.77 2.637V9.463l1.734-.867v7.978L12 12.975l-6.504 3.6z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.uub5b3bfk {
  fill: var(--svg-color--3fbced, #3fbced);
  d: path("M24 0H0v24h24z");
}

.ynwn50bfr {
  fill: var(--svg-color--fff, #fff);
  d: path("m12 18.001l-3.239-2.016l-1.686 1.019L12 20l4.995-3.005l-1.7-1.015L12 18.005zm0-11.894L7.495 8.492l-1.808-.789L12 4l6.418 3.699l-1.917.793l-4.5-2.38z");
}

</style>
