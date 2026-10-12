<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="y5xrsrbdz"/><circle class="mq68zybfy"/><path class="a-syrabih"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:solar-farm-sharp" /></template>
<style>
.a-syrabih {
  d: path("M6.75 5.75h1.5m7.5 0h1.5");
}

.mq68zybfy {
  cx: 12px;
  cy: 5.75px;
  r: 2.5px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y5xrsrbdz {
  d: path("M4.25 12.75h5.5l.12.74l.51 3.27l.12.74H2.75l.12-.74l.51-3.27l.12-.74zm10.75 0h5.5l.12.74l.51 3.27l.12.74H13.5l.12-.74l.51-3.27l.12-.74zM6.75 17.5v3.75m10.5-3.75v3.75");
}

</style>
