<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="i6libyn5d"/><path class="gcmba238s"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:met-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.gcmba238s {
  fill: var(--svg-color--fff, #fff);
  d: path("M4 10.515v6.055c0 .345.3.93 1.045.93s.945-.62.955-.93v-5.875A2.47 2.47 0 0 1 8.56 8.5A2.37 2.37 0 0 1 11 10.695v5.875c0 .345.29.93 1.01.93c.715 0 .99-.57.99-.815c-.01-1.91 0-5.78 0-5.99c0-.41.4-2.195 2.62-2.195A2.32 2.32 0 0 1 18 10.695v5.875c0 .4.34.93 1.05.93c.69 0 .94-.66.95-.93v-6.055c0-2.3-2.12-4.015-4.38-4.015a4.9 4.9 0 0 0-3.61 1.715A4.7 4.7 0 0 0 8.56 6.5C5.195 6.525 4 9.2 4 10.515");
}

.i6libyn5d {
  fill: var(--svg-color--7e61f8, #7e61f8);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
