<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dc7s40ben"/><path class="gms_xv68n"/><path class="yu-j7jb_g"/><path class="hf4n5umrc"/><path class="r3faxubne"/><path class="oifr9zbpt"/><path class="zvg9k5fuv"/><path class="nz5g1fb0o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:metric-drilldown-duotone-thin" /></template>
<style>
.dc7s40ben {
  fill: currentColor;
  d: path("M9 10a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.gms_xv68n {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hf4n5umrc {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M11.5 10.5 15 14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nz5g1fb0o {
  d: path("M11.5 10.5 15 14");
}

.oifr9zbpt {
  d: path("M4 20h16");
}

.r3faxubne {
  d: path("M4 4v16");
}

.yu-j7jb_g {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 20h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.zvg9k5fuv {
  d: path("M9 10a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
