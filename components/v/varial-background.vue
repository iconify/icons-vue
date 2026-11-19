<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="ucwmfmb4u"/><path class="aoa3ly6gz"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:varial-background" /></template>
<style>
.aoa3ly6gz {
  fill: var(--svg-color--fff, #fff);
  d: path("M4.413 6.326a.34.34 0 0 0-.357.519l8.138 12.858a.342.342 0 0 0 .63-.129c.981-6.675-1.172-11.658-8.41-13.248m12.351-2.142c.043-.086.186-.055.19.04q.165 3.21 2.995 4.665c.085.043.055.185-.04.19q-3.17.162-4.608 3.027c-.043.085-.186.055-.19-.04q-.165-3.21-2.995-4.665c-.085-.044-.055-.185.04-.19q3.17-.164 4.608-3.027");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.ucwmfmb4u {
  fill: var(--svg-color--0050ff, #0050ff);
  d: path("M24 0H0v24h24z");
}

</style>
