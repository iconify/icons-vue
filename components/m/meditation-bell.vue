<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fz0hinbmb"/><rect class="t4eapacis"/><path class="ij-cl4btt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:meditation-bell" /></template>
<style>
.fz0hinbmb {
  d: path("M4.25 9.75h12.5C16.75 13.5 14 16 10.5 16s-6.25-2.5-6.25-6.25");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ij-cl4btt {
  d: path("m16.75 9.75l4.5 4M6.07 7.22A4.5 4.5 0 0 1 8.25 4.1M3.61 6.78a7 7 0 0 1 1.94-3.73");
}

.t4eapacis {
  width: 12px;
  height: 2.75px;
  x: 4.5px;
  y: 18.5px;
  rx: 1.375px;
}

</style>
