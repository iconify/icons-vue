<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="cwgb59c-m"/><path class="tzxtpfb7v"/><path class="k8enhtbpo"/><path class="pfcm3lbpl"/><path class="qy_bscdws"/><path class="yhbbndf5c"/><path class="fd4ngbb9a"/><path class="zohykibek"/><path class="j49v8ng1j"/><path class="fop9i_hvr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:user-journey-duotone-bold" /></template>
<style>
.cwgb59c-m {
  fill: currentColor;
  d: path("M2 19a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.fd4ngbb9a {
  d: path("m6 17 4 -4");
}

.fop9i_hvr {
  d: path("M19 4a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.j49v8ng1j {
  d: path("m14 9 4 -4");
}

.k8enhtbpo {
  fill: currentColor;
  d: path("M19 4a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.pfcm3lbpl {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m6 17 4 -4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.qy_bscdws {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m14 9 4 -4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.tzxtpfb7v {
  fill: currentColor;
  d: path("M10 11a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.yhbbndf5c {
  d: path("M2 19a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.zohykibek {
  d: path("M10 11a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
