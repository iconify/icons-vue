<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><circle class="o86863f9l"/><path class="pmrceg31p"/><path class="cbohd9b_c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:scream-sharp" /></template>
<style>
.cbohd9b_c {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 9.75a1.25 1.75 0 0 1 0 3.5a1.25 1.75 0 0 1 0-3.5Zm-4.87 7.47a2 3-20 1 1-3.76 1.36a2 3-20 1 1 3.76-1.36Zm9.74 0a2 3 20 1 0 3.76 1.36a2 3 20 1 0-3.76-1.36ZM3.34 15.96L3 15.02m2.46.17l-.34-.94m15.54 1.71l.34-.94m-2.46.17l.34-.94");
}

.o86863f9l {
  cx: 12px;
  cy: 10px;
  r: 6px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pmrceg31p {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9.5 8h.01m4.99 0h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
