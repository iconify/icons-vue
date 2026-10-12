<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="csiuwxz_l"/><circle class="dtaoxebzb"/><path class="tha-1bije"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:secure-connection-sharp" /></template>
<style>
.csiuwxz_l {
  cx: 4.75px;
  cy: 13px;
  r: 2px;
}

.dtaoxebzb {
  cx: 19.25px;
  cy: 13px;
  r: 2px;
}

.tha-1bije {
  d: path("M6.75 13H9m6 0h2.25M9 10.5h6v5H9zm1.5 0v-3h3v3");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
