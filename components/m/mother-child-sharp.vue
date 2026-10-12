<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="pto36s2zd"/><path class="q0km1ub9z"/><circle class="jvv3of_em"/><path class="mwbu91bhj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:mother-child-sharp" /></template>
<style>
.jvv3of_em {
  cx: 18.75px;
  cy: 11.75px;
  r: 1.75px;
}

.mwbu91bhj {
  d: path("M16.25 21.25V18a2.5 2.5 0 0 1 5 0v3.25Z");
}

.pto36s2zd {
  cx: 8.5px;
  cy: 5.5px;
  r: 2.25px;
}

.q0km1ub9z {
  d: path("M3.25 21.25L5.1 12.4l.484-2.163l2.216.013h1.4l2.216-.013l.484 2.163l1.85 8.85Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
