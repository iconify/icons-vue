<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jirei-bba"/><path class="sfh31bcxq"/><path class="nzu-xuz8n"/><path class="qfaf8otig"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:printer-outline-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jirei-bba {
  d: path("M7 6.5V2h10v4.5");
}

.nzu-xuz8n {
  d: path("M4.5 12.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.qfaf8otig {
  d: path("M7 18v4h10v-4");
}

.sfh31bcxq {
  d: path("M2 10.5a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v4a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

</style>
