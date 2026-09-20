<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xnwdi1b1d"/><path class="hfnl5absx"/><path class="lrnxbrbud"/><path class="ece6v_boq"/><path class="er_d62ybc"/><path class="lw1netb9x"/><path class="d3kpl_b4o"/><path class="z89se__dl"/><path class="lwq-egybw"/><path class="rn-lfebhh"/><path class="dv5etjbjr"/><path class="x58_p1b1n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:plus-one-duotone-thin" /></template>
<style>
.d3kpl_b4o {
  d: path("M5 9a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.dv5etjbjr {
  d: path("M19.5 8v6");
}

.ece6v_boq {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 15a3 3 0 0 1 6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.er_d62ybc {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M19.5 8v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hfnl5absx {
  fill: currentColor;
  d: path("M13 9a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
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

.lrnxbrbud {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 15a3 3 0 0 1 6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.lw1netb9x {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M17 11h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.lwq-egybw {
  d: path("M13 9a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.rn-lfebhh {
  d: path("M12 15a3 3 0 0 1 6 0");
}

.x58_p1b1n {
  d: path("M17 11h5");
}

.xnwdi1b1d {
  fill: currentColor;
  d: path("M5 9a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.z89se__dl {
  d: path("M4 15a3 3 0 0 1 6 0");
}

</style>
