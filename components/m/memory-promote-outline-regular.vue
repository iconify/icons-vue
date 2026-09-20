<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="n0n63pb2v"/><path class="n-slc2cbp"/><path class="d1t4ffbbq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:memory-promote-outline-regular" /></template>
<style>
.d1t4ffbbq {
  d: path("M8 12.5h8");
}

.n-slc2cbp {
  d: path("M8.5 9.5 12 6l3.5 3.5");
}

.n0n63pb2v {
  d: path("M4 15v4h16v-4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
