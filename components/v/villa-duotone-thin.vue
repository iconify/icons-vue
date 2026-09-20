<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="auksz-3ux"/><path class="zwepyo6gf"/><path class="p_ahq1lnm"/><path class="y0er98b-g"/><path class="mi_rhabsp"/><path class="pm0e7ny3b"/><path class="tbo01n9ke"/><path class="s88iiwf1g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:villa-duotone-thin" /></template>
<style>
.auksz-3ux {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m2 11 6 -6 6 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mi_rhabsp {
  d: path("m2 11 6 -6 6 6");
}

.p_ahq1lnm {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m15 14 2 -2 2 2 2 -2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.pm0e7ny3b {
  d: path("M4 11v8h8v-8");
}

.s88iiwf1g {
  d: path("m15 19 2 -2 2 2 2 -2");
}

.tbo01n9ke {
  d: path("m15 14 2 -2 2 2 2 -2");
}

.y0er98b-g {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m15 19 2 -2 2 2 2 -2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.zwepyo6gf {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 11v8h8v-8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
