<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="i_jx4ibni"/><path class="dw2_-wujy"/><circle class="nc6i6rbeo"/><path class="gs8c1e75c"/><circle class="oa9ejwbnd"/><path class="xtka53bsh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:queue-sharp" /></template>
<style>
.dw2_-wujy {
  d: path("M3.75 15.75H7v-5.5H3v5.5z");
}

.gs8c1e75c {
  d: path("M10.75 15.75H14v-5.5h-4v5.5z");
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

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xtka53bsh {
  d: path("M17.75 15.75H21v-5.5h-4v5.5zM3 20h17.5m-1.25-1.25L20.5 20l-1.25 1.25");
}

</style>
