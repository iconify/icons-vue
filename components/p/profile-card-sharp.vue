<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="d71ra62vd"/><circle class="ozmcgbndl"/><path class="nwgaeub8v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:profile-card-sharp" /></template>
<style>
.d71ra62vd {
  d: path("M2.75 3.75h18.5v16.5H2.75zM12.5 9.5h8.75");
}

.nwgaeub8v {
  d: path("M13 12.75h4.5M6 16.5h12");
}

.ozmcgbndl {
  cx: 8px;
  cy: 10.25px;
  r: 3px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
