<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><circle class="iiep2hbuf"/><path class="d3boadcyy"/><circle class="v9wdgzl2y"/><path class="bl69p4_jc"/><path class="rkp-hlblu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:singer" /></template>
<style>
.bl69p4_jc {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.75 21.25v-2.5a3.75 3.75 0 0 1 7.5 0v2.5Zm-.5-13v-5.5l2.5 1");
}

.d3boadcyy {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 21.25v-2.5a3.75 3.75 0 0 1 7.5 0v2.5Z");
}

.iiep2hbuf {
  cx: 6.5px;
  cy: 10.5px;
  r: 2px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rkp-hlblu {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12.25 8.25h.01");
}

.v9wdgzl2y {
  cx: 17.5px;
  cy: 10.5px;
  r: 2px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
