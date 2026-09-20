<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xgscl2bdj"/><path class="aogdz07wp"/><path class="xr_8ruaxk"/><path class="rzyhl__ak"/><path class="gv3gpab3b"/><path class="zirb-hbnv"/><path class="dk-6jeb9s"/><path class="qm50txban"/><path class="cfyvl-o0i"/><path class="mi_m6achy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:trigger-event-duotone-thin" /></template>
<style>
.aogdz07wp {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M11.54 8.46a5 5 0 0 1 0 7.08");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.cfyvl-o0i {
  d: path("M16 12h4");
}

.dk-6jeb9s {
  d: path("M11.54 8.46a5 5 0 0 1 0 7.08");
}

.gv3gpab3b {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m17 9 3 3 -3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mi_m6achy {
  d: path("m17 9 3 3 -3 3");
}

.qm50txban {
  d: path("M13.66 6.34a8 8 0 0 1 0 11.32");
}

.rzyhl__ak {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M16 12h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.xgscl2bdj {
  fill: currentColor;
  d: path("M6 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.xr_8ruaxk {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M13.66 6.34a8 8 0 0 1 0 11.32");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.zirb-hbnv {
  d: path("M6 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
