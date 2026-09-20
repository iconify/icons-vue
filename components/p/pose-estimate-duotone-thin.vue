<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="eff5yibna"/><path class="oho0kmbto"/><path class="oiwjkbc_g"/><path class="u518r6bwr"/><path class="xh_jgyela"/><path class="k4e83vbdy"/><path class="pq9ly31-r"/><path class="y2-meob4g"/><path class="zp4961b8b"/><path class="sc-u_pmnm"/><path class="hcbabq6mn"/><path class="mk6myd_hq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:pose-estimate-duotone-thin" /></template>
<style>
.eff5yibna {
  fill: currentColor;
  d: path("M10 4a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.hcbabq6mn {
  d: path("m12 15 -5 5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k4e83vbdy {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m12 15 5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.mk6myd_hq {
  d: path("m12 15 5 5");
}

.oho0kmbto {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 6v9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.oiwjkbc_g {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m7 14 5 -5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.pq9ly31-r {
  d: path("M10 4a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.sc-u_pmnm {
  d: path("m17 14 -5 -5");
}

.u518r6bwr {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m17 14 -5 -5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.xh_jgyela {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m12 15 -5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.y2-meob4g {
  d: path("M12 6v9");
}

.zp4961b8b {
  d: path("m7 14 5 -5");
}

</style>
