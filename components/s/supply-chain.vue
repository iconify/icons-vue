<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="yrxf8qb1k"/><path class="jdagscxop"/><rect class="ekxin2b8i"/><path class="erfhgqbsg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:supply-chain" /></template>
<style>
.ekxin2b8i {
  width: 6.5px;
  height: 6.5px;
  x: 14.75px;
  y: 14.75px;
  rx: 1.5px;
}

.erfhgqbsg {
  d: path("M18 14.75V17M12 6h3.5A2.5 2.5 0 0 1 18 8.5v3m-2.25-2L18 11.75l2.25-2.25M12 18H8.5A2.5 2.5 0 0 1 6 15.5v-3m-2.25 2L6 12.25l2.25 2.25");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jdagscxop {
  d: path("M6 2.75V5");
}

.yrxf8qb1k {
  width: 6.5px;
  height: 6.5px;
  x: 2.75px;
  y: 2.75px;
  rx: 1.5px;
}

</style>
