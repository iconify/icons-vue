<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="ro-zg9bqv"/><path class="fnv8_cbyv"/><path class="lvqic1ifg"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:qanx-background" /></template>
<style>
.fnv8_cbyv {
  fill: var(--svg-color--fff, #fff);
  d: path("M8.652 14.503a3.1 3.1 0 0 1-1.67.472A2.88 2.88 0 0 1 4.002 12c0-1.752 1.28-2.977 2.976-2.977c1.697 0 2.977 1.225 2.977 2.977c0 .796-.268 1.488-.719 1.994zm.558-2.504c0-1.22-1.023-2.232-2.232-2.232c-1.205 0-2.232 1.015-2.232 2.232a2.25 2.25 0 0 0 2.232 2.232c1.5 0 2.232-1.235 2.232-2.232m3.892-2.977l-.688.462l.305.647l1.008 2.612h-2.21l-.338.744h2.85l.599 1.488h.907zM20 14.975h-.867l-2.854-4.598v4.598h-.744V9.022h.875l2.846 4.644V9.022H20z");
}

.ft5dv1b6b {
  fill: none;
}

.lvqic1ifg {
  fill: var(--svg-color--fff, #fff);
  d: path("M7.666 12.743h-1.06l2.146 2.232h1.053zm5.44-3.72h-.886l-2.381 5.952h.907z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.ro-zg9bqv {
  fill: var(--svg-color--00adee, #00adee);
  d: path("M24 0H0v24h24z");
}

</style>
