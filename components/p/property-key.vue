<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="vq4bz6b8z"/><path class="qgna_dwcr"/><path class="kyk6c_b5e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:property-key" /></template>
<style>
.kyk6c_b5e {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.75 14h8.5m-5.75 0v2.75M18.25 14v2.75m3-2.75v3");
}

.qgna_dwcr {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7.75 13h.01");
}

.vq4bz6b8z {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 17v-5.25q0-1 .78-1.62l3.44-2.76q.78-.62 1.56 0l3.44 2.76q.78.62.78 1.62V17q0 1-1 1h-8q-1 0-1-1");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
