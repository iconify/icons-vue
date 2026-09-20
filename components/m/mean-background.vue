<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGEc2eLMcq)" class="r4i437pya"/><path clip-rule="evenodd" class="d2d0_k5xb"/></g><defs><linearGradient id="SVGEc2eLMcq" x1="12" x2="12" y1="4.5" y2="19.5" gradientUnits="userSpaceOnUse"><stop class="ih7cttb9k"/><stop offset="1" class="gav1c7bmd"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:mean-background" /></template>
<style>
.d2d0_k5xb {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M19.5 4L12 6L4.5 4c0 1.69-.5 3.5-.5 3.5l3.19 8.74L12 20l4.81-3.76L20 7.5c-.05 0-.5-1.81-.5-3.5M12 7.5L6 6c0 1.475-.33 1.885-.33 1.885L8.5 15.25L10 16.5L7.5 8l3 1l1 7.75L12 18l.5-1.25l1-7.75l3-1l-2.5 8.5l1.5-1.25l2.83-7.365S18 7.255 18 6z");
}

.ft5dv1b6b {
  fill: none;
}

.gav1c7bmd {
  stop-color: var(--svg-color--b8091c, #b8091c);
}

.ih7cttb9k {
  stop-color: var(--svg-color--f40315, #f40315);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

</style>
