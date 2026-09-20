<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="xgscl2bdj"/><path class="lnx1h_bnf"/><path class="rss405b4d"/><path class="ql_xiaczr"/><path class="gmcwnnbyg"/><path class="zirb-hbnv"/><path class="dk-6jeb9s"/><path class="qm50txban"/><path class="cfyvl-o0i"/><path class="mi_m6achy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:trigger-event-duotone-regular" /></template>
<style>
.cfyvl-o0i {
  d: path("M16 12h4");
}

.dk-6jeb9s {
  d: path("M11.54 8.46a5 5 0 0 1 0 7.08");
}

.gmcwnnbyg {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m17 9 3 3 -3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.lnx1h_bnf {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M11.54 8.46a5 5 0 0 1 0 7.08");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.mi_m6achy {
  d: path("m17 9 3 3 -3 3");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ql_xiaczr {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M16 12h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.qm50txban {
  d: path("M13.66 6.34a8 8 0 0 1 0 11.32");
}

.rss405b4d {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M13.66 6.34a8 8 0 0 1 0 11.32");
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
