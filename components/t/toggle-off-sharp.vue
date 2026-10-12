<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="qp45nix1v"/><circle class="qhvrk_ymv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:toggle-off-sharp" /></template>
<style>
.qhvrk_ymv {
  cx: 8.25px;
  cy: 12px;
  r: 3px;
}

.qp45nix1v {
  d: path("M2.75 6.5h18.5v11H2.75z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
