<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="pr33wacdx"/><circle class="ywfc_z2mj"/><path class="mr52dqd-k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:route-x-sharp" /></template>
<style>
.mr52dqd-k {
  d: path("M8.5 18.5h8.25a3.25 3.25 0 0 0 0-6.5h-9.5a3.25 3.25 0 0 1 0-6.5h8.25");
}

.pr33wacdx {
  cx: 6px;
  cy: 18.5px;
  r: 2.5px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ywfc_z2mj {
  cx: 18px;
  cy: 5.5px;
  r: 2.5px;
}

</style>
