<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="n0n63pb2v"/><path class="ylrudh6bl"/><path class="l2oprob0y"/><path class="qr1iqpomq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:memory-quota-outline-regular" /></template>
<style>
.l2oprob0y {
  d: path("M17 5v6");
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

.qr1iqpomq {
  d: path("M9 8h6");
}

.ylrudh6bl {
  d: path("M7 5v6");
}

</style>
