<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="n0n63pb2v"/><path class="jotdonbiv"/><path class="a-p6m2b3f"/><path class="ux6apgnet"/><path class="aes764-qd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:memory-audit-outline-thin" /></template>
<style>
.a-p6m2b3f {
  d: path("M10.5 6H16");
}

.aes764-qd {
  d: path("M10.5 10H16");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jotdonbiv {
  d: path("M7 6a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.n0n63pb2v {
  d: path("M4 15v4h16v-4");
}

.ux6apgnet {
  d: path("M7 10a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
