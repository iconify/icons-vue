<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ha05_q27d"/><path class="w2b54lbpr"/><path class="xb-kv0a1i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:tap-outline-thin" /></template>
<style>
.ha05_q27d {
  d: path("M5 4v6h11v3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.w2b54lbpr {
  d: path("M3 4h5");
}

.xb-kv0a1i {
  d: path("m16 15 2.5 2.5a3 3 0 1 1 -5 0Z");
}

</style>
