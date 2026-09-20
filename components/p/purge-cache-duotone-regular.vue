<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="av-olcbyp"/><path class="zieizabtx"/><path class="rdx10mbki"/><path class="y4yg_xrrs"/><path class="zp4rqbtqe"/><path class="ml5vh8o3m"/><path class="ngom1s3yg"/><path class="v7v_f9j5h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:purge-cache-duotone-regular" /></template>
<style>
.av-olcbyp {
  fill: currentColor;
  d: path("M3 10a2 2 0 0 1 2 -2h8a2 2 0 0 1 2 2v8a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.ml5vh8o3m {
  d: path("M17 5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.ngom1s3yg {
  d: path("M20 9a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rdx10mbki {
  fill: currentColor;
  d: path("M20 9a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.v7v_f9j5h {
  d: path("M18 13a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.y4yg_xrrs {
  fill: currentColor;
  d: path("M18 13a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.zieizabtx {
  fill: currentColor;
  d: path("M17 5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.zp4rqbtqe {
  d: path("M3 10a2 2 0 0 1 2 -2h8a2 2 0 0 1 2 2v8a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

</style>
