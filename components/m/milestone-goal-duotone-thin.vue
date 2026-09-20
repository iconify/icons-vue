<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vpuel0dtu"/><path class="bnrf8ghpe"/><path class="fio18jbgq"/><path class="lu9velljz"/><path class="crv4i00bu"/><path class="lulmb9b1a"/><path class="sfjortb-o"/><path class="ucuiysazu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:milestone-goal-duotone-thin" /></template>
<style>
.bnrf8ghpe {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 4h16v12H4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.crv4i00bu {
  d: path("M4 3v18");
}

.fio18jbgq {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 7v5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lu9velljz {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M9.5 9.5 12 12l2.5 -2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.lulmb9b1a {
  d: path("M4 4h16v12H4");
}

.sfjortb-o {
  d: path("M12 7v5");
}

.ucuiysazu {
  d: path("M9.5 9.5 12 12l2.5 -2.5");
}

.vpuel0dtu {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 3v18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
