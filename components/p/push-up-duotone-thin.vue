<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="umge8xb0s"/><path class="itae-9boz"/><path class="jh_3rl5dl"/><path class="n_qrh_dko"/><path class="rpp4spbxo"/><path class="a3zqh3bcj"/><path class="hpmnlabtt"/><path class="yg08zkbcc"/><path class="zmo9x5bsa"/><path class="bod4n0b3z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:push-up-duotone-thin" /></template>
<style>
.a3zqh3bcj {
  d: path("M2 8a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.bod4n0b3z {
  d: path("M2 18h20");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hpmnlabtt {
  d: path("M6 9h12");
}

.itae-9boz {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 9h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.jh_3rl5dl {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8 9v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.n_qrh_dko {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M18 9v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.rpp4spbxo {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 18h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.umge8xb0s {
  fill: currentColor;
  d: path("M2 8a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.yg08zkbcc {
  d: path("M8 9v7");
}

.zmo9x5bsa {
  d: path("M18 9v7");
}

</style>
