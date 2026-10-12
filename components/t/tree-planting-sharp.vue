<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="an9l3ju_g"/><path class="zwmeo2bod"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:tree-planting-sharp" /></template>
<style>
.an9l3ju_g {
  cx: 9.5px;
  cy: 8px;
  r: 5.25px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zwmeo2bod {
  d: path("M9.5 13.25v5m-6.5 3c1-2.25 3.5-3 6.5-3s5.5.75 6.5 3Zm15.5-18V13m-1.75 0h3.5v4.5h-3.5v-1.75Z");
}

</style>
