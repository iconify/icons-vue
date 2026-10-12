<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ixm9b82zq"/><circle class="t3wpecpwg"/><path class="u9ss38v1g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:trackball" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ixm9b82zq {
  d: path("M2.75 15.25a6.5 6.5 0 0 1 6.5-6.5h5.5a6.5 6.5 0 0 1 6.5 6.5v3a3 3 0 0 1-3 3H5.75a3 3 0 0 1-3-3Z");
}

.t3wpecpwg {
  cx: 9.25px;
  cy: 15px;
  r: 3.25px;
}

.u9ss38v1g {
  d: path("M16.75 12.25v3.5");
}

</style>
