<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ug3d9xb1l"/><path class="ugv0mtd4a"/><path class="tcotthakx"/><path class="ir4gqcb4x"/><path class="ds000fbnl"/><path class="bj2hlhbfp"/><path class="ukjt4fb6s"/><path class="ids981bkm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:self-consistency-duotone-regular" /></template>
<style>
.bj2hlhbfp {
  d: path("M3 12h12");
}

.ds000fbnl {
  d: path("M3 7h12");
}

.ids981bkm {
  d: path("m17 11 2 2 3 -3");
}

.ir4gqcb4x {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m17 11 2 2 3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.tcotthakx {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 17h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ug3d9xb1l {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 7h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ugv0mtd4a {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 12h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ukjt4fb6s {
  d: path("M3 17h12");
}

</style>
