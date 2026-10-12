<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="stb55jbvy"/><rect class="zxgo491ks"/><rect class="u5g7_8l9r"/><path class="ie6pbzb_j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:nasal-spray" /></template>
<style>
.ie6pbzb_j {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M13.75 5.5h.01m-2.51 2.25h.01M13.5 9h.01");
}

.stb55jbvy {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.75 2.75c0 3.5-1.5 6.25-3.5 9.5c-.75 1.25 0 2.25 1.5 2.25h2.5m8-2.75l.5-5.25a.75.75 0 0 1 1.5 0l.5 5.25Z");
}

.u5g7_8l9r {
  width: 6.5px;
  height: 7.25px;
  x: 13.75px;
  y: 14px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2px;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.zxgo491ks {
  width: 8.5px;
  height: 2.25px;
  x: 12.75px;
  y: 11.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1px;
}

</style>
