<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="yyatzac7g"/><rect class="t1z0sd6ud"/><path class="gqrs6_i3t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:workflow-ai" /></template>
<style>
.gqrs6_i3t {
  d: path("M9.25 6H11a2 2 0 0 1 2 2v8a2 2 0 0 1-2 2H9.25M13 12h.75m3.75-3.75q.45 3.3 3.75 3.75q-3.3.45-3.75 3.75q-.45-3.3-3.75-3.75q3.3-.45 3.75-3.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.t1z0sd6ud {
  width: 6.5px;
  height: 6.5px;
  x: 2.75px;
  y: 14.75px;
  rx: 1.75px;
}

.yyatzac7g {
  width: 6.5px;
  height: 6.5px;
  x: 2.75px;
  y: 2.75px;
  rx: 1.75px;
}

</style>
