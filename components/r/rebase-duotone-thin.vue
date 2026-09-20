<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nrmo-yb4e"/><path class="atmhlzoyy"/><path class="xn5xrlbtk"/><path class="ppivcbbzp"/><path class="x3k3riida"/><path class="hehuylblo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:rebase-duotone-thin" /></template>
<style>
.atmhlzoyy {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m5 14 6 -6h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hehuylblo {
  d: path("m16 5 3 3 -3 3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nrmo-yb4e {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M5 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ppivcbbzp {
  d: path("M5 4v16");
}

.x3k3riida {
  d: path("m5 14 6 -6h8");
}

.xn5xrlbtk {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m16 5 3 3 -3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
