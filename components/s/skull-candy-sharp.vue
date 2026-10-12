<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="j-vy8fs4u"/><circle class="h40q97-sv"/><circle class="xsyi1tbgh"/><circle class="weiruygfv"/><path class="j7vio8fah"/><path class="vd5vw1bsd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:skull-candy-sharp" /></template>
<style>
.h40q97-sv {
  cx: 8.9px;
  cy: 11px;
  r: 1.9px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j-vy8fs4u {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.75c4.5 0 8 3.25 8 7.5c0 2.5-1.25 4.25-3 5.25v5.75H7V15.5c-1.75-1-3-2.75-3-5.25c0-4.25 3.5-7.5 8-7.5Z");
}

.j7vio8fah {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 14.25h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.vd5vw1bsd {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 17.75h5M12 17v1.5");
}

.weiruygfv {
  cx: 12px;
  cy: 6.25px;
  r: 1.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xsyi1tbgh {
  cx: 15.1px;
  cy: 11px;
  r: 1.9px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
