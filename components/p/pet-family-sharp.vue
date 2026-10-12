<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="t6k6kbb4z"/><path class="ug_qh2xpm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:pet-family-sharp" /></template>
<style>
.t6k6kbb4z {
  cx: 6.5px;
  cy: 6px;
  r: 2.5px;
}

.ug_qh2xpm {
  d: path("M2.75 21.25V15a3.75 3.75 0 0 1 7.5 0v6.25ZM13.25 9l1.5 1.5h2l1.5-1.5v5.125l-.75.375l.75.75v6h-5v-6l.75-.75l-.75-.375V13Zm5 11.75h3V15.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
