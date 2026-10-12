<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="nztd_gkzu"/><circle class="dyb220bek"/><path class="uu-n7tbdi"/><path class="eyxk-rc0a"/><path class="oifdkcjlz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:panda-sharp" /></template>
<style>
.dyb220bek {
  cx: 12px;
  cy: 13.5px;
  r: 7.5px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.eyxk-rc0a {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8.75 12.5h.01m6.49 0h.01");
}

.nztd_gkzu {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.82 9.24a2.75 2.75 0 1 1 2.92-2.49a7.5 7.5 0 0 0-2.92 2.49Zm9.44-2.49a2.75 2.75 0 1 1 2.92 2.49a7.5 7.5 0 0 0-2.92-2.49Z");
}

.oifdkcjlz {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.25 17h1.5");
}

.uu-n7tbdi {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 12.75a1.75 2.25 0 1 0 3.5 0a1.75 2.25 0 1 0-3.5 0Zm6.5 0a1.75 2.25 0 1 0 3.5 0a1.75 2.25 0 1 0-3.5 0Z");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
