<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jnldlo15l"/><rect class="jcod8fb3k"/><path class="eden49bgc"/><circle class="m_ubk9bxa"/><circle class="npsx14byy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:street-cart" /></template>
<style>
.eden49bgc {
  d: path("m17.5 11l3.75-2");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jcod8fb3k {
  width: 14.5px;
  height: 4.25px;
  x: 3px;
  y: 9.75px;
  rx: 1.25px;
}

.jnldlo15l {
  d: path("M4.5 9.75C5.25 7.25 7.5 6 10.25 6s5 1.25 5.75 3.75Z");
}

.m_ubk9bxa {
  cx: 7px;
  cy: 18.75px;
  r: 2.5px;
}

.npsx14byy {
  cx: 14px;
  cy: 18.75px;
  r: 2.5px;
}

</style>
