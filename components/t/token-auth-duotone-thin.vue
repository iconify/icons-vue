<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nmlr5bcid"/><path class="vefr08bem"/><path class="r0xtqjbuh"/><path class="sy-mrrsuv"/><path class="it83nbbll"/><path class="a_lj6jt5i"/><path class="zy54a7bml"/><path class="zn_a46_dj"/><path class="yg3iw3bty"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:token-auth-duotone-thin" /></template>
<style>
.a_lj6jt5i {
  d: path("M9 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.it83nbbll {
  d: path("M5 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.nmlr5bcid {
  fill: currentColor;
  d: path("M2 12a4 4 0 0 1 4 -4h5a4 4 0 0 1 4 4 4 4 0 0 1 -4 4H6a4 4 0 0 1 -4 -4");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.r0xtqjbuh {
  fill: currentColor;
  d: path("M9 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.sy-mrrsuv {
  d: path("M2 12a4 4 0 0 1 4 -4h5a4 4 0 0 1 4 4 4 4 0 0 1 -4 4H6a4 4 0 0 1 -4 -4");
}

.vefr08bem {
  fill: currentColor;
  d: path("M5 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.yg3iw3bty {
  d: path("M21 12v2.5");
}

.zn_a46_dj {
  d: path("M18 12v3");
}

.zy54a7bml {
  d: path("M17 12h4");
}

</style>
