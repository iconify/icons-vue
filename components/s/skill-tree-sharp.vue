<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="acqd5qb6b"/><circle class="tz8y8z-uo"/><circle class="k-k8m_51k"/><circle class="iv8fwcb7u"/><circle class="yssos9efq"/><path class="gkrqf9ahv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:skill-tree-sharp" /></template>
<style>
.acqd5qb6b {
  cx: 12px;
  cy: 19px;
  r: 2.25px;
}

.gkrqf9ahv {
  d: path("m10.54 17.29l-3.08-3.58m6 3.58l3.08-3.58M6 9.75v-2.5m12 2.5v-2.5");
}

.iv8fwcb7u {
  cx: 6px;
  cy: 5px;
  r: 2.25px;
}

.k-k8m_51k {
  cx: 18px;
  cy: 12px;
  r: 2.25px;
}

.tz8y8z-uo {
  cx: 6px;
  cy: 12px;
  r: 2.25px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yssos9efq {
  cx: 18px;
  cy: 5px;
  r: 2.25px;
}

</style>
