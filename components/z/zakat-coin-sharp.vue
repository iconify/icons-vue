<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="skhsrsbjf"/><path class="p-8tvcbog"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:zakat-coin-sharp" /></template>
<style>
.p-8tvcbog {
  d: path("M13.55 5.2a1.4 1.4 0 1 0 0 2.6l-2.258-1.3l2.258-1.3m-10.8 9.3H6l3 1.75h4.75v2.5h-4.5M14.5 18l4.25-2.25a1.4 1.4 0 0 1 1.75 2.2l-5.5 3.3H6.5L2.75 20");
}

.skhsrsbjf {
  cx: 13px;
  cy: 6.5px;
  r: 3.75px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
