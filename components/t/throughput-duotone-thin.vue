<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ovzzbs_1x"/><path class="m8a93sb6x"/><path class="ki9ikb40y"/><path class="qt6bebbgj"/><path class="zuuudpbwi"/><path class="dzvfone4k"/><path class="k134iabcj"/><path class="cks97xg-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:throughput-duotone-thin" /></template>
<style>
.cks97xg-s {
  d: path("m14 13 3 3 -3 3");
}

.dzvfone4k {
  d: path("m14 5 3 3 -3 3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k134iabcj {
  d: path("M3 16h14");
}

.ki9ikb40y {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 16h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.m8a93sb6x {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m14 5 3 3 -3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ovzzbs_1x {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 8h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.qt6bebbgj {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m14 13 3 3 -3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.zuuudpbwi {
  d: path("M3 8h14");
}

</style>
