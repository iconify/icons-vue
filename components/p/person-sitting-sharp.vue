<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="eoenbp1iq"/><path class="nz70flb9l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:person-sitting-sharp" /></template>
<style>
.eoenbp1iq {
  cx: 9.5px;
  cy: 4.75px;
  r: 2px;
}

.nz70flb9l {
  d: path("M9.5 9.5v6.25h5.25v5.5m-5.25-10l3 1.75M6 9.75v11.5m0-3h5.75");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
