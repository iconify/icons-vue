<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="e3q3hpiyy"/><path class="kezat3tkx"/><path class="ocjprzbva"/><path class="hpy_80lju"/><path class="kgzfjfb2m"/><path class="mglly3fuq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:stack-trace-duotone-bold" /></template>
<style>
.e3q3hpiyy {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 3v18h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hpy_80lju {
  d: path("M3 3v18h8");
}

.kezat3tkx {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M9 7v10h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.kgzfjfb2m {
  d: path("M9 7v10h6");
}

.mglly3fuq {
  d: path("M15 10v3h4");
}

.ocjprzbva {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M15 10v3h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
