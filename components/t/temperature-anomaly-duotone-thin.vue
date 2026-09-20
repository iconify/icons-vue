<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gms_xv68n"/><path class="yu-j7jb_g"/><path class="sb_u66zcg"/><path class="gnvqcobbd"/><path class="r3faxubne"/><path class="oifr9zbpt"/><path class="nyl8f3o_r"/><path class="bxgmjusbj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:temperature-anomaly-duotone-thin" /></template>
<style>
.bxgmjusbj {
  d: path("m6 17 4 -4 3 3 4 -4");
}

.gms_xv68n {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.gnvqcobbd {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m6 17 4 -4 3 3 4 -4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nyl8f3o_r {
  d: path("M6 13h13");
}

.oifr9zbpt {
  d: path("M4 20h16");
}

.r3faxubne {
  d: path("M4 4v16");
}

.sb_u66zcg {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 13h13");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.yu-j7jb_g {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 20h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
