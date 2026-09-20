<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="eff5yibna"/><path class="dg38x0kzm"/><path class="yjbv1fxpe"/><path class="vqrmwn19b"/><path class="wrpmqtm4c"/><path class="d--p2qc0m"/><path class="pq9ly31-r"/><path class="y2-meob4g"/><path class="zp4961b8b"/><path class="sc-u_pmnm"/><path class="hcbabq6mn"/><path class="mk6myd_hq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:pose-estimate-duotone-bold" /></template>
<style>
.d--p2qc0m {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m12 15 5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.dg38x0kzm {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 6v9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.eff5yibna {
  fill: currentColor;
  d: path("M10 4a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.hcbabq6mn {
  d: path("m12 15 -5 5");
}

.mk6myd_hq {
  d: path("m12 15 5 5");
}

.pq9ly31-r {
  d: path("M10 4a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.sc-u_pmnm {
  d: path("m17 14 -5 -5");
}

.vqrmwn19b {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m17 14 -5 -5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.wrpmqtm4c {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m12 15 -5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.y2-meob4g {
  d: path("M12 6v9");
}

.yjbv1fxpe {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m7 14 5 -5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.zp4961b8b {
  d: path("m7 14 5 -5");
}

</style>
