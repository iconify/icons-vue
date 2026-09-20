<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="xgscl2bdj"/><path class="m5_4n02th"/><path class="fx_eqlb4y"/><path class="bgia9xbjb"/><path class="t_57glb-y"/><path class="zirb-hbnv"/><path class="dk-6jeb9s"/><path class="qm50txban"/><path class="cfyvl-o0i"/><path class="mi_m6achy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:trigger-event-duotone-bold" /></template>
<style>
.bgia9xbjb {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M16 12h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.cfyvl-o0i {
  d: path("M16 12h4");
}

.dk-6jeb9s {
  d: path("M11.54 8.46a5 5 0 0 1 0 7.08");
}

.fx_eqlb4y {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M13.66 6.34a8 8 0 0 1 0 11.32");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.m5_4n02th {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M11.54 8.46a5 5 0 0 1 0 7.08");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.mi_m6achy {
  d: path("m17 9 3 3 -3 3");
}

.qm50txban {
  d: path("M13.66 6.34a8 8 0 0 1 0 11.32");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.t_57glb-y {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m17 9 3 3 -3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.xgscl2bdj {
  fill: currentColor;
  d: path("M6 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.zirb-hbnv {
  d: path("M6 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
