<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gms_xv68n"/><path class="yu-j7jb_g"/><path class="m8byhbt3q"/><path class="b2zuoxbqm"/><path class="z0jk47bno"/><path class="r3faxubne"/><path class="oifr9zbpt"/><path class="qr1iqpomq"/><path class="pt-3kkb2k"/><path class="ikiprn9sq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:summary-metric-duotone-thin" /></template>
<style>
.b2zuoxbqm {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M9 11h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

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

.ikiprn9sq {
  d: path("M9 14h6");
}

.m8byhbt3q {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M9 8h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.oifr9zbpt {
  d: path("M4 20h16");
}

.pt-3kkb2k {
  d: path("M9 11h6");
}

.qr1iqpomq {
  d: path("M9 8h6");
}

.r3faxubne {
  d: path("M4 4v16");
}

.yu-j7jb_g {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 20h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.z0jk47bno {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M9 14h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
