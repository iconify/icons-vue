<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="mc_m_91cr"/><circle class="n81udiknj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:reminder-bell-sharp" /></template>
<style>
.mc_m_91cr {
  d: path("M10.5 4.5a5 5 0 0 0-5 5v3.25l-1.5 3h13l-1.5-3V9.5a5 5 0 0 0-5-5Zm-2 14.25v2h4v-2");
}

.n81udiknj {
  cx: 19px;
  cy: 4.5px;
  r: 1.5px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
