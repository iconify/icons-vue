<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="hogdls_gf"/><rect class="jwda1wbwq"/><path class="tg7pxm2zo"/><circle class="j2ov4djsy"/><path class="tvc__j9qb"/><circle class="riohgnbtm"/><path class="g27ahybtf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:trolley" /></template>
<style>
.g27ahybtf {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M17.5 19h.01");
}

.hogdls_gf {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 4.75h2l2.4 12H18.7");
}

.j2ov4djsy {
  cx: 10.5px;
  cy: 19px;
  r: 2.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jwda1wbwq {
  width: 8.5px;
  height: 6.25px;
  x: 9.75px;
  y: 7.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1.25px;
}

.riohgnbtm {
  cx: 17.5px;
  cy: 19px;
  r: 2.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.tg7pxm2zo {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 7.75V5.5h4v2.25");
}

.tvc__j9qb {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10.5 19h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
