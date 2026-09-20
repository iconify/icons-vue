<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ert_saboi"/><path class="zbeypivls"/><path class="otp5h22rb"/><path class="jcxg2bbvb"/><path class="fyyr_6-1m"/><path class="ue-dwjbmw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:splitter-duotone-thin" /></template>
<style>
.ert_saboi {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 12h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.fyyr_6-1m {
  d: path("m10 12 4 -4h7");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jcxg2bbvb {
  d: path("M2 12h8");
}

.otp5h22rb {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m10 12 4 4h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ue-dwjbmw {
  d: path("m10 12 4 4h7");
}

.zbeypivls {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m10 12 4 -4h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
