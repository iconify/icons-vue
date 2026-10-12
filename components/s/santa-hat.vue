<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gc_e4ccxh"/><circle class="taq4_hb2a"/><rect class="nk135eb1n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:santa-hat" /></template>
<style>
.gc_e4ccxh {
  d: path("m4.92 15.06l1.66-5.62Q7 8 8.17 7.06l2.66-2.12Q12 4 13.47 4.28l1.06.19q1.47.28 2.19 1.6l1.35 4.05A2 2 0 0 0 17.02 13l-.42 2.5q-.1 1-1.1 1H6q-1.5 0-1.08-1.44");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nk135eb1n {
  width: 16.5px;
  height: 4.75px;
  x: 2.75px;
  y: 16.5px;
  rx: 2.25px;
}

.taq4_hb2a {
  cx: 18.75px;
  cy: 12px;
  r: 2px;
}

</style>
