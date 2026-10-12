<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="fhcsjwttb"/><path class="tark0cc2e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:timer-off-sharp" /></template>
<style>
.fhcsjwttb {
  cx: 12px;
  cy: 13.5px;
  r: 7.75px;
}

.tark0cc2e {
  d: path("M9.75 2.75h4.5m-2.25 0v3m0 7.75V8.75a4.75 4.75 0 0 1 4.75 4.75Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
