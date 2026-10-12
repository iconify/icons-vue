<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="i_jx4ibni"/><path class="cferbzb4q"/><circle class="nc6i6rbeo"/><path class="efubx7bod"/><circle class="oa9ejwbnd"/><path class="atbhsubfk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:queue" /></template>
<style>
.atbhsubfk {
  d: path("M17.75 15.75h2.5A.75.75 0 0 0 21 15v-3a1.75 1.75 0 0 0-1.75-1.75h-.5A1.75 1.75 0 0 0 17 12v3a.75.75 0 0 0 .75.75M3 20h17.5m-1.25-1.25L20.5 20l-1.25 1.25");
}

.cferbzb4q {
  d: path("M3.75 15.75h2.5A.75.75 0 0 0 7 15v-3a1.75 1.75 0 0 0-1.75-1.75h-.5A1.75 1.75 0 0 0 3 12v3a.75.75 0 0 0 .75.75");
}

.efubx7bod {
  d: path("M10.75 15.75h2.5A.75.75 0 0 0 14 15v-3a1.75 1.75 0 0 0-1.75-1.75h-.5A1.75 1.75 0 0 0 10 12v3a.75.75 0 0 0 .75.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i_jx4ibni {
  cx: 5px;
  cy: 5.75px;
  r: 1.5px;
}

.nc6i6rbeo {
  cx: 12px;
  cy: 5.75px;
  r: 1.5px;
}

.oa9ejwbnd {
  cx: 19px;
  cy: 5.75px;
  r: 1.5px;
}

</style>
