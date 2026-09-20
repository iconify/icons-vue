<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gms_xv68n"/><path class="i7-hwrk0u"/><path class="lntfr9p2v"/><path class="r3faxubne"/><path class="ws1d0fbts"/><path class="odutg_b9y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:nap-duotone-thin" /></template>
<style>
.gms_xv68n {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i7-hwrk0u {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M20 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.lntfr9p2v {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 7c0 12 16 12 16 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.odutg_b9y {
  d: path("M4 7c0 12 16 12 16 0");
}

.r3faxubne {
  d: path("M4 4v16");
}

.ws1d0fbts {
  d: path("M20 4v16");
}

</style>
