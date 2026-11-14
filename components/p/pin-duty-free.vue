<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="t48ck1beq"/><path class="r_5ej1lys"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pin-duty-free" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.r_5ej1lys {
  d: path("M9 11V7a3 3 0 0 1 6 0v4");
}

.t48ck1beq {
  d: path("M7.34 8h9.32a2.625 2.625 0 0 1 2.608 2.324l.894 7.75A2.625 2.625 0 0 1 17.555 21H6.445a2.625 2.625 0 0 1-2.607-2.926l.894-7.75A2.625 2.625 0 0 1 7.34 8");
}

</style>
