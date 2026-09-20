<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="g6btd475d"/><path class="bkuclybie"/><path class="nuhfel7ej"/><path class="eqpdiibxq"/><path class="wlr6jzb8s"/><path class="mn-a1zb6m"/><path class="e2kgfl2ea"/><path class="s25-orfog"/><path class="jv3d31_7h"/><path class="mqnae981n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:reunion-duotone-thin" /></template>
<style>
.bkuclybie {
  fill: currentColor;
  d: path("M17 9a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.e2kgfl2ea {
  d: path("M2 15a3 3 0 0 1 6 0");
}

.eqpdiibxq {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M16 15a3 3 0 0 1 6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.g6btd475d {
  fill: currentColor;
  d: path("M3 9a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
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

.jv3d31_7h {
  d: path("M16 15a3 3 0 0 1 6 0");
}

.mn-a1zb6m {
  d: path("M3 9a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.mqnae981n {
  d: path("m9 11 3 3 3 -3");
}

.nuhfel7ej {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 15a3 3 0 0 1 6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s25-orfog {
  d: path("M17 9a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.wlr6jzb8s {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m9 11 3 3 3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
