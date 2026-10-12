<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="ui70-tr_j"/><circle class="zz9p51bci"/><path class="l57ozh_fr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:remote-sharp" /></template>
<style>
.l57ozh_fr {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10 12.25h.01m3.99 0h.01M10 16h.01M14 16h.01");
}

.ui70-tr_j {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.25 2.75h9.5v18.5h-9.5z");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.zz9p51bci {
  cx: 12px;
  cy: 7px;
  r: 1.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
