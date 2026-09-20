<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tm88wrbeh"/><path class="rdx3slmde"/><path class="ha96dokbt"/><path class="nqq-ml3sz"/><path class="b_fzcqbeu"/><path class="ui32hib9b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:sunburn-risk-duotone-thin" /></template>
<style>
.b_fzcqbeu {
  d: path("M5 20a7 7 0 0 1 14 0");
}

.ha96dokbt {
  d: path("M5.5 7H8");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nqq-ml3sz {
  d: path("M16 7h2.5");
}

.rdx3slmde {
  d: path("M8.5 7a3.5 3.5 0 1 0 7 0 3.5 3.5 0 1 0 -7 0");
}

.tm88wrbeh {
  fill: currentColor;
  d: path("M8.5 7a3.5 3.5 0 1 0 7 0 3.5 3.5 0 1 0 -7 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.ui32hib9b {
  d: path("M5 20h14");
}

</style>
