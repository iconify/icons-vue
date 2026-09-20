<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="z9do-djry"/><path class="i_lu0jbgc"/><path class="l1_xhdcdr"/><path class="k-tnn71bj"/><path class="phi687keh"/><path class="znfuzdoyp"/><path class="mt0duqbnk"/><path class="luzoskb2e"/><path class="l1lmw_bdv"/><path class="saj3disjq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:stargazing-duotone-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i_lu0jbgc {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 6h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.k-tnn71bj {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M13 11h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.l1_xhdcdr {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M16 8v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.l1lmw_bdv {
  d: path("M13 11h6");
}

.luzoskb2e {
  d: path("M16 8v6");
}

.mt0duqbnk {
  d: path("M4 6h6");
}

.phi687keh {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 20c4 -3 14 -3 18 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.saj3disjq {
  d: path("M3 20c4 -3 14 -3 18 0");
}

.z9do-djry {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M7 3v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.znfuzdoyp {
  d: path("M7 3v6");
}

</style>
