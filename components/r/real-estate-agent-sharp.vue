<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="e7wxh0bvw"/><path class="crg1i76ng"/><path class="v0nxv_bai"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:real-estate-agent-sharp" /></template>
<style>
.crg1i76ng {
  d: path("M2.75 21.25V15.5h12.5v5.75Z");
}

.e7wxh0bvw {
  cx: 9px;
  cy: 7.25px;
  r: 3.75px;
}

.v0nxv_bai {
  d: path("m9 15.5l-.9 3l.9 1.25l.9-1.25Zm6-5.75v-4l.59-.47l1.95-1.56l.59-.47l.59.47l1.94 1.56l.59.47v4.75H15z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
