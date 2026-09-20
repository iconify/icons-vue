<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="ffg559uqm"/><path clip-rule="evenodd" class="g9n3ocs5x"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:stjuno-background" /></template>
<style>
.ffg559uqm {
  fill: var(--svg-color--e40570, #e40570);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.g9n3ocs5x {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M20 12a8 8 0 1 1-16 0a8 8 0 0 1 16 0m-.518 0a7.482 7.482 0 1 1-14.965 0a7.482 7.482 0 0 1 14.965 0m-7.953 4.235v.942h.942v-.942h1.411v-.94h-1.411v-3.53l1.647 1.647l.705-.706l-1.646-1.647h2.117v-.941h-2.117l1.646-1.647l-.705-.706l-1.647 1.647V7.294h-.942v2.118L9.882 7.765l-.706.706l1.647 1.647H8.706v.94h2.117l-1.647 1.648l.706.706l1.647-1.647v3.53h-1.411v.94z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
