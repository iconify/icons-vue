<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="gtxwlbcag"/><path class="g7s01wbra"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:purchase-order-sharp" /></template>
<style>
.g7s01wbra {
  d: path("M13.75 2.75v5.5h5.5m-11 3.5h3.5M8.25 15h2.5m3.75-1h6l.75 7.25h-7.5Zm1.25 0v-2.5h3.5V14");
}

.gtxwlbcag {
  d: path("M10.5 21.25H4.75V2.75h9l5.5 5.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
