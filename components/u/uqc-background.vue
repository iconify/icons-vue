<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="chs1w281t"/><path class="c0sfktb0y"/><path class="lg3rmib3n"/><path class="yok-fwbmu"/><path class="zpjn8achi"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:uqc-background" /></template>
<style>
.c0sfktb0y {
  fill: var(--svg-color--fff, #fff);
  d: path("M14.838 14.064V4.258l2.58 5.161v10.15c-.773.173-2.58.173-2.58.173zl-1.548 3.097h-2.58l-1.55-3.097v5.678s-1.587.025-2.58-.174V9.42l2.58-5.161v9.806z");
}

.chs1w281t {
  fill: var(--svg-color--cf3339, #cf3339);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.lg3rmib3n {
  fill: var(--svg-color--fff, #fff);
  d: path("M6.58 19.568C5.507 19.318 4 18.255 4 17.176V4.258l2.58 5.161zm10.84 0c1.074-.25 2.58-1.313 2.58-2.392V4.258l-2.58 5.161z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.yok-fwbmu {
  fill: var(--svg-color--fff, #fff);
  d: path("M6.58 9.42L4 4.257h5.161zm10.84 0L20 4.257h-5.161zm-2.582 10.32H9.16l1.549-2.58h2.58z");
}

.zpjn8achi {
  fill: var(--svg-color--fff, #fff);
  d: path("M10.709 17.16L9.16 19.74v-5.677zm4.129 2.58l-1.549-2.58l1.549-3.097z");
}

</style>
