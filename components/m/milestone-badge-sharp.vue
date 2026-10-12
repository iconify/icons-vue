<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="ncm5f0d6i"/><circle class="dld8vub9v"/><path class="egcnl37_d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:milestone-badge-sharp" /></template>
<style>
.dld8vub9v {
  cx: 12px;
  cy: 8.5px;
  r: 5.75px;
}

.egcnl37_d {
  d: path("m10.75 6.75l1.5-1.25v6");
}

.ncm5f0d6i {
  d: path("M8 12.63L6.5 20.5l2.25-1.25l1.5 1.75l.25-6.95A5.75 5.75 0 0 1 8 12.63Zm8 0l1.5 7.87l-2.25-1.25l-1.5 1.75l-.25-6.95a5.75 5.75 0 0 0 2.5-1.42Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
