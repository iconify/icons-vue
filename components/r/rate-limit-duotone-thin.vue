<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="oqv9_8b1v"/><path class="ert_saboi"/><path class="hs_rar6oe"/><path class="x5zrl2b2s"/><path class="h90oycbac"/><path class="o0-3vqblf"/><path class="jcxg2bbvb"/><path class="h5uycs4sy"/><path class="wp75hkmty"/><path class="y2lgilb0y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:rate-limit-duotone-thin" /></template>
<style>
.ert_saboi {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 12h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.h5uycs4sy {
  d: path("M2 16h8");
}

.h90oycbac {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M13 12h9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hs_rar6oe {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 16h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.jcxg2bbvb {
  d: path("M2 12h8");
}

.o0-3vqblf {
  d: path("M2 8h8");
}

.oqv9_8b1v {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 8h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.wp75hkmty {
  d: path("M11 7v10");
}

.x5zrl2b2s {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M11 7v10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.y2lgilb0y {
  d: path("M13 12h9");
}

</style>
