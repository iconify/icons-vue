<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="no_v-sbjp"/><path class="vxtvt1e5w"/><path class="qa-jr78us"/><path class="rz8xw-bse"/><path class="ffw_pwyfz"/><path class="kfdmhd64i"/><path class="njsdrxbyk"/><path class="xlsprdnsf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:sub-question-duotone-regular" /></template>
<style>
.ffw_pwyfz {
  d: path("M12.62 3.5a7 7 0 1 1 -5.24 0");
}

.kfdmhd64i {
  d: path("m15 15 6 6");
}

.njsdrxbyk {
  d: path("M7.5 8a2.5 2.5 0 1 1 2.5 2.5");
}

.no_v-sbjp {
  fill: currentColor;
  d: path("M9 13a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qa-jr78us {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m15 15 6 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.rz8xw-bse {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M7.5 8a2.5 2.5 0 1 1 2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.vxtvt1e5w {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12.62 3.5a7 7 0 1 1 -5.24 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.xlsprdnsf {
  d: path("M9 13a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
