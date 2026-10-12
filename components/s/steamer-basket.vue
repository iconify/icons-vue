<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="g8stv6j_u"/><rect class="l_aksfuwe"/><path class="pkxnteb1g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:steamer-basket" /></template>
<style>
.g8stv6j_u {
  d: path("M4.25 7.5a7.75 3.25 0 0 1 15.5 0Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l_aksfuwe {
  width: 18.5px;
  height: 10.75px;
  x: 2.75px;
  y: 10.5px;
  rx: 2.5px;
}

.pkxnteb1g {
  d: path("M2.75 15.75h18.5");
}

</style>
