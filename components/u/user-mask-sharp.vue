<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="avgcxc5xk"/><circle class="cibw8q46d"/><circle class="t2x7kg3eo"/><path class="tsqj-fcfp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:user-mask-sharp" /></template>
<style>
.avgcxc5xk {
  d: path("m7.25 8.25l1.5-4.5l.19-.736L9.7 3h4.6l.76.014l.19.736l1.5 4.5Zm-4 0h17.5");
}

.cibw8q46d {
  cx: 8px;
  cy: 15px;
  r: 2.75px;
}

.t2x7kg3eo {
  cx: 16px;
  cy: 15px;
  r: 2.75px;
}

.tsqj-fcfp {
  d: path("M10.75 15h2.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
