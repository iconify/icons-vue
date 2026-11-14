<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="t6a0n_ezt"/><path class="xncuyrj0j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:permit-holders-sign" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.t6a0n_ezt {
  d: path("M6 2.5h12A3.5 3.5 0 0 1 21.5 6v6a3.5 3.5 0 0 1-3.5 3.5H6A3.5 3.5 0 0 1 2.5 12V6A3.5 3.5 0 0 1 6 2.5m6 13v6");
}

.xncuyrj0j {
  d: path("M6.5 12.5v-7H8a2 2 0 0 1 0 4H6.5m6-.5l2 2l4-4");
}

</style>
