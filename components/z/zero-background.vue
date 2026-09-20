<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="w0cy7fbys"/><path clip-rule="evenodd" class="zz9_kjbgp"/><path clip-rule="evenodd" class="ol2ut1bzv"/><path class="v-rgcdcnb"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:zero-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.ol2ut1bzv {
  fill: var(--svg-color--000, #000);
  fill-rule: evenodd;
  d: path("M12 19.118a7.12 7.12 0 1 0 0-14.24a7.12 7.12 0 0 0 0 14.24m0 .44a7.56 7.56 0 1 0 0-15.121a7.56 7.56 0 0 0 0 15.121");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.v-rgcdcnb {
  fill: var(--svg-color--000, #000);
  d: path("M15 8.5H9V10h3.65L9 14.35v1.15h6V14h-3.59L15 9.665z");
}

.w0cy7fbys {
  fill: var(--svg-color--fce058, #fce058);
  d: path("M24 0H0v24h24z");
}

.zz9_kjbgp {
  fill: var(--svg-color--000, #000);
  fill-rule: evenodd;
  d: path("M12 19.56a7.561 7.561 0 0 0 5.346-12.906A7.56 7.56 0 1 0 12 19.56m0 .44a8 8 0 1 0 0-15.998A8 8 0 0 0 12 20");
}

</style>
