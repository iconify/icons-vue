<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="eff5yibna"/><path class="a5euidb9j"/><path class="ja2btdm4a"/><path class="v0ok-fbvy"/><path class="m9qosmcgp"/><path class="nm8bg81hz"/><path class="pq9ly31-r"/><path class="y2-meob4g"/><path class="zp4961b8b"/><path class="sc-u_pmnm"/><path class="hcbabq6mn"/><path class="mk6myd_hq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:pose-estimate-duotone-regular" /></template>
<style>
.a5euidb9j {
  stroke-width: var(--svg-stroke-width--5px, 5px);
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

.ja2btdm4a {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m7 14 5 -5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.m9qosmcgp {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m12 15 -5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.mk6myd_hq {
  d: path("m12 15 5 5");
}

.nm8bg81hz {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m12 15 5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pq9ly31-r {
  d: path("M10 4a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.sc-u_pmnm {
  d: path("m17 14 -5 -5");
}

.v0ok-fbvy {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m17 14 -5 -5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.y2-meob4g {
  d: path("M12 6v9");
}

.zp4961b8b {
  d: path("m7 14 5 -5");
}

</style>
