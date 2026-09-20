<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="qok472_6y"/><path class="b-igcmojr"/><circle class="tycblpsev"/><g class="mgmcp5b_b"><path class="p6_itfb7e"/><circle class="gzeibpb1b"/></g><circle class="jxshosbdt"/><circle class="v117yuefw"/><path class="u-mo00bsy"/><path class="glev_jx1v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:trackball" /></template>
<style>
.b-igcmojr {
  fill: var(--svg-color--fcc21b, #fcc21b);
  d: path("M42.72 128h42.03c7.73 0 14-6.27 14-14V69.98H28.72V114c0 7.73 6.27 14 14 14");
}

.glev_jx1v {
  fill: var(--svg-color--ed6c30, #ed6c30);
  d: path("m57.41 41.35l-1.18-5.45c-8.71 1.9-16.2 7.05-21.16 14.11l4.54 3.24a29.42 29.42 0 0 1 17.8-11.9m13.84-5.45l-1.18 5.45c7.33 1.61 13.64 5.95 17.8 11.9l4.54-3.24C87.46 42.95 79.96 37.8 71.25 35.9");
}

.gzeibpb1b {
  cx: 63.74px;
  cy: 69.98px;
  r: 23.29px;
  stroke-width: var(--svg-stroke-width--4px, 4px);
}

.jxshosbdt {
  cx: 63.74px;
  cy: 69.98px;
  r: 21.34px;
  fill: var(--svg-color--2f2f2f, #2f2f2f);
}

.mgmcp5b_b {
  fill: none;
  stroke: var(--svg-color--fff, #fff);
  stroke-miterlimit: 10;
}

.p6_itfb7e {
  stroke-width: var(--svg-stroke-width--3px, 3px);
  d: path("M63.74 46.69c12.86 0 23.29 10.43 23.29 23.29s-10.42 23.3-23.29 23.3s-23.29-10.43-23.29-23.3s10.43-23.29 23.29-23.29z");
}

.qok472_6y {
  fill: none;
  stroke: var(--svg-color--2f2f2f, #2f2f2f);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M17.67 3v2.46c0 8.82 7.15 15.97 15.97 15.97h14.74c8.82 0 15.97 7.15 15.97 15.97v12.42");
}

.tycblpsev {
  cx: 63.74px;
  cy: 69.98px;
  r: 35.02px;
  fill: var(--svg-color--fcc21b, #fcc21b);
}

.u-mo00bsy {
  fill: none;
  stroke: var(--svg-color--fff, #fff);
  stroke-linecap: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M53.44 72.28s-.69-4.46 3.03-8.52m3.83-3.85l.92-.5");
}

.v117yuefw {
  cx: 63.74px;
  cy: 69.98px;
  r: 16.55px;
  fill: var(--svg-color--40c0e7, #40c0e7);
}

</style>
