<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="fhcsjwttb"/><path class="bnwycijld"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:timer-play-sharp" /></template>
<style>
.bnwycijld {
  d: path("M9.75 2.75h4.5m-2.25 0v3M17.5 8l1.75-1.75m-8.35 4.62l3.95 2.26l.65.37l-.65.37l-3.95 2.26l-.65.37v-6z");
}

.fhcsjwttb {
  cx: 12px;
  cy: 13.5px;
  r: 7.75px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
