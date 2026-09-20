<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="mumfproca"/><path class="h2kgcsbzm"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:zlk-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.h2kgcsbzm {
  fill: var(--svg-color--fff, #fff);
  d: path("M5.082 8.18c0-.155.082-.302.216-.375l6.347-3.745a.43.43 0 0 1 .433-.004l6.62 3.749a.43.43 0 0 1 .22.38v7.628a.43.43 0 0 1-.22.38l-6.625 3.749a.43.43 0 0 1-.432 0l-6.343-3.749a.43.43 0 0 1-.216-.376zm1.937.81a.44.44 0 0 0-.208.371v5.414a.44.44 0 0 0 .212.376l4.614 2.767a.43.43 0 0 0 .44 0L14.11 16.7a.44.44 0 0 0-.004-.752l-4.052-2.378a.45.45 0 0 1-.216-.38V8.024a.432.432 0 0 0-.657-.372l-2.162 1.34z");
}

.mumfproca {
  fill: var(--svg-color--000, #000);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
