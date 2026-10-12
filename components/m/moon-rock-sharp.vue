<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="pbf6q-b3f"/><circle class="a9v2pgbhx"/><circle class="l4apx-b4t"/><circle class="yj9-2ib_t"/><circle class="bqx8eybot"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:moon-rock-sharp" /></template>
<style>
.a9v2pgbhx {
  cx: 13px;
  cy: 11.5px;
  r: 2.75px;
}

.bqx8eybot {
  cx: 9px;
  cy: 9px;
  r: 0.75px;
}

.l4apx-b4t {
  cx: 8px;
  cy: 14.5px;
  r: 1px;
}

.pbf6q-b3f {
  d: path("m4.51 10.77l2.23-3.79l1.01-1.73l1.97-.34l3.31-.57L15 4l1.45 1.38l2.85 2.74l1.45 1.38l-.3 1.98l-.65 4.29l-.3 1.98l-1.88.69l-3.74 1.37l-1.88.69l-1.9-.61l-3.2-1.03l-1.9-.61l-.5-1.94l-.5-1.87l-.5-1.94z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yj9-2ib_t {
  cx: 15.5px;
  cy: 16.75px;
  r: 0.75px;
}

</style>
