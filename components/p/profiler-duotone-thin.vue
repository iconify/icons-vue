<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rzbhhg_xy"/><path class="hmaihv3yx"/><path class="nlorwyu1r"/><path class="jv75tobai"/><path class="atoje4bsc"/><path class="uchchabsk"/><path class="bbj1r8bpd"/><path class="vybq366mg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:profiler-duotone-thin" /></template>
<style>
.atoje4bsc {
  d: path("M2 6h20");
}

.bbj1r8bpd {
  d: path("M4 14h12");
}

.hmaihv3yx {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 10h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jv75tobai {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 18h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nlorwyu1r {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 14h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.rzbhhg_xy {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 6h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.uchchabsk {
  d: path("M2 10h14");
}

.vybq366mg {
  d: path("M4 18h6");
}

</style>
