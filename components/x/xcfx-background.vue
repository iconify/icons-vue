<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="xd8z-na_m"/><path clip-rule="evenodd" class="g8z0mzu6a"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:xcfx-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.g8z0mzu6a {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M18.792 8.193a.24.24 0 0 0-.14.236a.24.24 0 0 0 .027.093a7.53 7.53 0 1 1-4.527-3.736a.24.24 0 0 0 .314-.223a.23.23 0 0 0-.163-.224a8 8 0 1 0 4.785 3.952a.23.23 0 0 0-.296-.098m-6.79 8.047a4.234 4.234 0 1 0 0-8.469a4.234 4.234 0 0 0 0 8.469m0 .47a4.706 4.706 0 1 0 0-9.412a4.706 4.706 0 0 0 0 9.412m6.117-10.823a1.412 1.412 0 1 1-2.824 0a1.412 1.412 0 0 1 2.824 0m.47 0a1.882 1.882 0 1 1-3.764 0a1.882 1.882 0 0 1 3.765 0");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.xd8z-na_m {
  fill: var(--svg-color--ff914c, #ff914c);
  d: path("M24 0H0v24h24z");
}

</style>
