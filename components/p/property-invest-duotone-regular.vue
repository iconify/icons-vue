<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="pqqiwbo9y"/><path class="r3lb1g6ab"/><path class="uwm_c9biv"/><path class="a6e_o0bju"/><path class="dvfmj91gv"/><path class="kp1e7wcsa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:property-invest-duotone-regular" /></template>
<style>
.a6e_o0bju {
  d: path("m3 11 9 -9 9 9");
}

.dvfmj91gv {
  d: path("M6 11v10h12V11");
}

.kp1e7wcsa {
  d: path("m9 19 2 -2 2 2 2 -2");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pqqiwbo9y {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m3 11 9 -9 9 9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.r3lb1g6ab {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M6 11v10h12V11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.uwm_c9biv {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m9 19 2 -2 2 2 2 -2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
