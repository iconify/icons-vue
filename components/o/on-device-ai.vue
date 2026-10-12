<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="f0emd8bls"/><path class="a6k8m0b_o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:on-device-ai" /></template>
<style>
.a6k8m0b_o {
  d: path("M10.5 18h3M12 6.75q.45 3.3 3.75 3.75q-3.3.45-3.75 3.75q-.45-3.3-3.75-3.75q3.3-.45 3.75-3.75");
}

.f0emd8bls {
  width: 12.5px;
  height: 18.5px;
  x: 5.75px;
  y: 2.75px;
  rx: 2.75px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
