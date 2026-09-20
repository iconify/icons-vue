<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xgscl2bdj"/><path class="q73r75vfo"/><path class="rzyhl__ak"/><path class="gv3gpab3b"/><path class="tmqpmbchx"/><path class="zirb-hbnv"/><path class="cfyvl-o0i"/><path class="mi_m6achy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:trigger-webhook-duotone-thin" /></template>
<style>
.cfyvl-o0i {
  d: path("M16 12h4");
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

.q73r75vfo {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M5 6.8a6 6 0 1 1 0 10.4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.rzyhl__ak {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M16 12h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.tmqpmbchx {
  d: path("M5 6.8a6 6 0 1 1 0 10.4");
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
