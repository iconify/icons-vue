<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zrtnu5wgy"/><rect class="duwz3z9hh"/><path class="ii43j_jdm"/><circle class="ii4uyg_2s"/><circle class="sbpdo7bey"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:trolleybus" /></template>
<style>
.duwz3z9hh {
  width: 18.5px;
  height: 9px;
  x: 2.75px;
  y: 8.5px;
  rx: 2.5px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ii43j_jdm {
  d: path("M6.25 12.25h11.5");
}

.ii4uyg_2s {
  cx: 7px;
  cy: 17.75px;
  r: 2.5px;
}

.sbpdo7bey {
  cx: 17px;
  cy: 17.75px;
  r: 2.5px;
}

.zrtnu5wgy {
  d: path("M2.75 2.75h18.5M7.5 8.5l4.75-5.75M11.5 8.5l4.75-5.75");
}

</style>
