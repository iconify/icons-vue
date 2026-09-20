<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="xgscl2bdj"/><path class="g5iyc4bvs"/><path class="nwdk136nn"/><path class="k3jn9bb1q"/><path class="vd_ltu4xs"/><path class="zirb-hbnv"/><path class="jlfl_ccwj"/><path class="wn519caci"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:webhook-out-duotone-regular" /></template>
<style>
.g5iyc4bvs {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M11 6.8a6 6 0 0 1 0 10.4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.jlfl_ccwj {
  d: path("M14 12h8");
}

.k3jn9bb1q {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m19 9 3 3 -3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.nwdk136nn {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M14 12h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.vd_ltu4xs {
  d: path("M11 6.8a6 6 0 0 1 0 10.4");
}

.wn519caci {
  d: path("m19 9 3 3 -3 3");
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
