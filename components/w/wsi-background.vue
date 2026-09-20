<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="j8r2s2blt"/><path class="mmksevb6k"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:wsi-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.j8r2s2blt {
  fill: var(--svg-color--013662, #013662);
  d: path("M24 0H0v24h24z");
}

.mmksevb6k {
  fill: var(--svg-color--fff, #fff);
  d: path("M10.667 4H9.334v6.222l1.333-3.546zM7.969 7.111H5.333l3.023 9.778h2.235l1.391-4.56l1.427 4.56h2.236l3.022-9.778h-2.582l-1.574 4.871l-1.52-4.87H11.01l-1.573 4.87zM14.667 4h-1.333v2.676l1.333 3.546zM9.334 17.333h1.333V20H9.334zm5.333 0h-1.333V20h1.333z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
