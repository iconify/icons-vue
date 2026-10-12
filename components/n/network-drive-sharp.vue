<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="xelf5tbxg"/><circle class="ix0sepbgl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:network-drive-sharp" /></template>
<style>
.ix0sepbgl {
  cx: 12px;
  cy: 19.5px;
  r: 1.5px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xelf5tbxg {
  d: path("M4.75 5.25v-2.5h6.1l.6.8l.6.7l.6.8h6.6V14H4.75v-2.5Zm7.25 9.5v3M2.75 19.5H10m4.25 0h7");
}

</style>
