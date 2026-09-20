<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="bd7jitbjr"/><path class="zerutheyi"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:yoshi-background" /></template>
<style>
.bd7jitbjr {
  fill: var(--svg-color--47dba7, #47dba7);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.zerutheyi {
  fill: var(--svg-color--000, #000);
  d: path("M15.892 6.444a34.5 34.5 0 0 1-3.953 5.787c-1.355-1.317-2.804-3.166-4.39-5.604c1.13-1.548 2.588-2.569 4.113-2.625c1.327-.047 2.917.917 4.23 2.442m-4.912 7.74L11.19 20c-3.82-.339-6.305-3.364-5.684-8.136c.146-1.12.457-2.211.89-3.2c0 0 2.267 3.492 4.583 5.52m2.093-.094l.207 5.835c3.788-.612 6.047-3.802 5.087-8.517a10.8 10.8 0 0 0-1.153-3.073a34 34 0 0 1-4.14 5.755");
}

</style>
