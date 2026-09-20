<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="fcm-vrp0v"/><path clip-rule="evenodd" class="vz_xnhywb"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:txau-background" /></template>
<style>
.fcm-vrp0v {
  fill: var(--svg-color--e3ba4f, #e3ba4f);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.vz_xnhywb {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M19.53 12a7.53 7.53 0 1 1-15.06 0a7.53 7.53 0 0 1 15.06 0m.47 0a8 8 0 1 1-16 0a8 8 0 0 1 16 0m-7.53 4.235v-.94h-.94c-1.13 0-1.412-.942-1.412-1.413V9.647c0-.753.94-.941 1.411-.941h.942c1.129 0 1.411.941 1.411 1.412v.47h1.412v-.94c0-1.507-1.882-1.883-2.823-1.883h-.942c-2.258 0-2.823 1.256-2.823 1.882v4.235c0 1.883 1.882 2.353 2.823 2.353zM15.295 12H12v.941h1.882v3.294h1.412z");
}

</style>
