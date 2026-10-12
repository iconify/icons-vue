<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="yk9jlhlfm"/><circle class="hnv9gbb9i"/><circle class="iq3w1nbpg"/><circle class="dzjafpb3d"/><circle class="io3g52bpb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:paw-print-check-sharp" /></template>
<style>
.dzjafpb3d {
  cx: 15px;
  cy: 5.75px;
  r: 2.25px;
}

.hnv9gbb9i {
  cx: 4.75px;
  cy: 11px;
  r: 2px;
}

.io3g52bpb {
  cx: 19.25px;
  cy: 11px;
  r: 2px;
}

.iq3w1nbpg {
  cx: 9px;
  cy: 5.75px;
  r: 2.25px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yk9jlhlfm {
  d: path("M12 12.25c-2.75 0-6 3.5-6 6.25V21h2.75c1.25 0 2-.5 3.25-.5s2 .5 3.25.5H18v-2.5c0-2.75-3.25-6.25-6-6.25Z");
}

</style>
