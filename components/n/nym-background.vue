<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="acj9wsb7i"/><path clip-rule="evenodd" class="bm03v0n8g"/><path class="rxa-1smea"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:nym-background" /></template>
<style>
.acj9wsb7i {
  fill: var(--svg-color--181b1e, #181b1e);
  d: path("M24 0H0v24h24z");
}

.bm03v0n8g {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M20 12a8 8 0 1 0-16 0a8 8 0 0 0 16 0m-.941 0a7.06 7.06 0 1 0-14.12 0a7.06 7.06 0 0 0 14.12 0");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.rxa-1smea {
  fill: var(--svg-color--fff, #fff);
  d: path("M7.765 16.701V7.308a6.4 6.4 0 0 1 1.411-.955l5.647 8.8v-8.8a6.5 6.5 0 0 1 1.412.993v9.36c-.428.373-.902.69-1.412.941L9.176 8.82v8.828a7.5 7.5 0 0 1-1.411-.946");
}

</style>
