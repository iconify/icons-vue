<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="nqkir3lvj"/><path class="c48smxb5m"/><path class="mqx1fpbzs"/><path class="r8p1fm0mz"/><path class="h5m00ybuy"/><path class="ap_bu5bso"/><path class="z5anc_e2t"/><path class="xj9o_6b5o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:sync-two-way-duotone-bold" /></template>
<style>
.ap_bu5bso {
  d: path("m15 6 3 3 -3 3");
}

.c48smxb5m {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m15 6 3 3 -3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.h5m00ybuy {
  d: path("M4 9h14");
}

.mqx1fpbzs {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 15h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nqkir3lvj {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 9h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.r8p1fm0mz {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m9 12 -3 3 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.xj9o_6b5o {
  d: path("m9 12 -3 3 3 3");
}

.z5anc_e2t {
  d: path("M6 15h14");
}

</style>
