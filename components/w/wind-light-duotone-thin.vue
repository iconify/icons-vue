<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="l0chbpn3h"/><path class="trrhg5btj"/><path class="byz9m5b8d"/><path class="nx6-lsb9m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:wind-light-duotone-thin" /></template>
<style>
.byz9m5b8d {
  d: path("M3 8h16");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l0chbpn3h {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 8h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nx6-lsb9m {
  d: path("M5 15h16");
}

.trrhg5btj {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M5 15h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
