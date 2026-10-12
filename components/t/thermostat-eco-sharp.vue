<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="dbgvcxwad"/><path class="rs46lbc6f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:thermostat-eco-sharp" /></template>
<style>
.dbgvcxwad {
  cx: 12px;
  cy: 12px;
  r: 9.25px;
}

.rs46lbc6f {
  d: path("M12 4.75v1.5M5.75 9.5L7 10m11.25-.5L17 10m-8.25 6.5c.25-3.75 2-5.75 6.5-6.75c-.25 3.75-2 5.75-6.5 6.75Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
