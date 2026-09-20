<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gms_xv68n"/><path class="yu-j7jb_g"/><path class="zpb80rb_h"/><path class="ffwhp4k4j"/><path class="r3faxubne"/><path class="oifr9zbpt"/><path class="bw_to0b8d"/><path class="him6j9cua"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:variance-duotone-thin" /></template>
<style>
.bw_to0b8d {
  d: path("M7 12h12");
}

.ffwhp4k4j {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M7 17 19 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.gms_xv68n {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.him6j9cua {
  d: path("M7 17 19 5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.oifr9zbpt {
  d: path("M4 20h16");
}

.r3faxubne {
  d: path("M4 4v16");
}

.yu-j7jb_g {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 20h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.zpb80rb_h {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M7 12h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
