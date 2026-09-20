<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="xu3q-b_rm"/><path class="yc_5gkigy"/><path class="kw6-bpbhi"/><path class="eq8p65fcb"/><path class="sxlwlmkmh"/><path class="r7xk8o29f"/><path class="tcxfk34nj"/><path class="pyew6cbwi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:sudoku-duotone-regular" /></template>
<style>
.eq8p65fcb {
  d: path("M4 4v16h16V4Z");
}

.kw6-bpbhi {
  fill: currentColor;
  d: path("M15 16a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
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

.pyew6cbwi {
  d: path("M15 16a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.r7xk8o29f {
  d: path("M12 4v16");
}

.sxlwlmkmh {
  d: path("M4 12h16");
}

.tcxfk34nj {
  d: path("M7 8a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.xu3q-b_rm {
  fill: currentColor;
  d: path("M4 4v16h16V4Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.yc_5gkigy {
  fill: currentColor;
  d: path("M7 8a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
