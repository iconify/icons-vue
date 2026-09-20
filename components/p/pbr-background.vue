<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="n47n983_g"/><path class="anmcivmsy"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:pbr-background" /></template>
<style>
.anmcivmsy {
  fill: var(--svg-color--fff, #fff);
  d: path("M20 10.6a1.6 1.6 0 1 1-3.201 0a1.6 1.6 0 0 1 3.201 0M4 13.176c.44-.324 1.728-.976 3.352-.976c1.056 0 2.472.52 3.832 1.012c1.244.452 2.44.888 3.26.888c1.308 0 1.828-.172 1.944-.268c-.412.4-1.6 1.168-3.168 1.168c-1.04 0-2.684-.536-4.252-1.048c-1.424-.464-2.784-.904-3.56-.904c-.668 0-1.216.084-1.408.128m12.4.64l-.012.016l.012-.012zM10.552 10.6c-1.624 0-2.912.652-3.352.976c.192-.04.74-.128 1.408-.128c.776 0 2.136.44 3.56.904c1.568.512 3.216 1.048 4.252 1.048a4.85 4.85 0 0 0 3.18-1.18l-.012.012c-.116.096-.636.268-1.944.268c-.82 0-2.016-.436-3.26-.888c-1.36-.496-2.776-1.012-3.832-1.012");
}

.ft5dv1b6b {
  fill: none;
}

.n47n983_g {
  fill: var(--svg-color--e0077d, #e0077d);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
