<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xzin226yh"/><path class="ja4e6ac_k"/><path class="yjik3t7vc"/><path class="h9i3bw3au"/><path class="n6_f133dv"/><path class="upuk2bbmi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:two-phase-duotone-thin" /></template>
<style>
.h9i3bw3au {
  d: path("m5 8 2 2 3.5 -3.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ja4e6ac_k {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m5 16 2 2 3.5 -3.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.n6_f133dv {
  d: path("m5 16 2 2 3.5 -3.5");
}

.upuk2bbmi {
  d: path("M15.5 5H18v14h-2.5");
}

.xzin226yh {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m5 8 2 2 3.5 -3.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.yjik3t7vc {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M15.5 5H18v14h-2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
