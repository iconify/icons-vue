<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="m_yp0c6fw"/><rect class="c311pobrm"/><rect class="ki_lxpbjl"/><path class="ryr12639v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:mooring-bollard" /></template>
<style>
.c311pobrm {
  width: 6.5px;
  height: 10.25px;
  x: 8.75px;
  y: 8.25px;
  rx: 0.75px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ki_lxpbjl {
  width: 13px;
  height: 2.75px;
  x: 5.5px;
  y: 18.5px;
  rx: 0.75px;
}

.m_yp0c6fw {
  d: path("M5.5 8.25a6.5 4.5 0 0 1 13 0Z");
}

.ryr12639v {
  d: path("M2.75 15.5c2.75 0 3.75-3 9.25-3s6.5 3 9.25 3");
}

</style>
