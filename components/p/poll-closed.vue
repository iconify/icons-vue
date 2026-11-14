<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="t78ktbbbj"/><path class="eq4om0bjd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:poll-closed" /></template>
<style>
.eq4om0bjd {
  d: path("M16 15.5V14a2 2 0 0 1 4 0v1.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.t78ktbbbj {
  d: path("M3 20.5V14m4 6.5V9m4 11.5v-17m5.688 12h2.625a2.19 2.19 0 0 1 2.187 2.188v1.625a2.19 2.19 0 0 1-2.187 2.187h-2.625a2.19 2.19 0 0 1-2.188-2.187v-1.625a2.19 2.19 0 0 1 2.188-2.188");
}

</style>
