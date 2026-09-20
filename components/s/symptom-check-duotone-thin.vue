<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zyr0_hpav"/><path class="y4_6s7b5v"/><path class="sxexd9boz"/><path class="aoxrbobxu"/><path class="p4162b_hg"/><path class="j3tm7xb5y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:symptom-check-duotone-thin" /></template>
<style>
.aoxrbobxu {
  d: path("M14 8h4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j3tm7xb5y {
  d: path("M14 15h4");
}

.p4162b_hg {
  d: path("m6 15 2 2 4 -4");
}

.sxexd9boz {
  d: path("m6 8 2 2 4 -4");
}

.y4_6s7b5v {
  d: path("M4 5a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2v14a2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2Z");
}

.zyr0_hpav {
  fill: currentColor;
  d: path("M4 5a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2v14a2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
