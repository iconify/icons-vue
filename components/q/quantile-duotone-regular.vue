<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="pd-i35blz"/><path class="iulb4mb6k"/><path class="jx95sabgb"/><path class="cfzejz4bs"/><path class="zd3ngbg5b"/><path class="r3faxubne"/><path class="oifr9zbpt"/><path class="z29yzbtbb"/><path class="mmi5hvbvz"/><path class="xmro9gb_f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:quantile-duotone-regular" /></template>
<style>
.cfzejz4bs {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M9 8v10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.iulb4mb6k {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 20h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.jx95sabgb {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m6 17 3 -3 3 -3 3 3 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.mmi5hvbvz {
  d: path("M9 8v10");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.oifr9zbpt {
  d: path("M4 20h16");
}

.pd-i35blz {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.r3faxubne {
  d: path("M4 4v16");
}

.xmro9gb_f {
  d: path("M15 8v10");
}

.z29yzbtbb {
  d: path("m6 17 3 -3 3 -3 3 3 3 3");
}

.zd3ngbg5b {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M15 8v10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
