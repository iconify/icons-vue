<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gms_xv68n"/><path class="yu-j7jb_g"/><path class="r4-d7jvjb"/><path class="q0d_gbhsb"/><path class="gs3es-zcn"/><path class="r3faxubne"/><path class="oifr9zbpt"/><path class="x3ookvx2e"/><path class="kuui-zbsa"/><path class="c08_j9b_a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:staleness-marker-duotone-thin" /></template>
<style>
.c08_j9b_a {
  d: path("m19.5 11.5 -3 3");
}

.gms_xv68n {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.gs3es-zcn {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m19.5 11.5 -3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kuui-zbsa {
  d: path("m16.5 11.5 3 3");
}

.oifr9zbpt {
  d: path("M4 20h16");
}

.q0d_gbhsb {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m16.5 11.5 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.r3faxubne {
  d: path("M4 4v16");
}

.r4-d7jvjb {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m7 17 4 -4h3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.x3ookvx2e {
  d: path("m7 17 4 -4h3");
}

.yu-j7jb_g {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 20h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
