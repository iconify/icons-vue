<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="e0-vo3x_e"/><path class="otkll89xj"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:ppc-background" /></template>
<style>
.e0-vo3x_e {
  fill: var(--svg-color--3cb054, #3cb054);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.otkll89xj {
  fill: var(--svg-color--fff, #fff);
  d: path("M5.5 4c10.487.4 14.526 6.845 12.49 12.604A6.18 6.18 0 0 1 15.519 20c.052-.231.113-.462.147-.702c.763-4.489-.676-9.894-7.714-12.88c5.6 3.422 7.861 9.511 5.244 13.44c-4.446.711-7.696-3.183-7.696-7.671z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
