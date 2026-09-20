<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="a2c_btbtq"/><path class="kf-dg5j1v"/><path class="t9rz8abmm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:mop-duotone-thin" /></template>
<style>
.a2c_btbtq {
  fill: currentColor;
  d: path("M8 11c-1 4 -2 7 -2 9h12c0 -2 -1 -5 -2 -9Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kf-dg5j1v {
  d: path("M12 2v9");
}

.t9rz8abmm {
  d: path("M8 11c-1 4 -2 7 -2 9h12c0 -2 -1 -5 -2 -9Z");
}

</style>
