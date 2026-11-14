<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="d0m1d-vxr"/><path class="a42ux9bpc"/><path class="ojjncdbgw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pull-door-sign" /></template>
<style>
.a42ux9bpc {
  d: path("M11 12c-4.5 0-7 1.5-7 5.5");
}

.d0m1d-vxr {
  d: path("M9.5 2.5h12v19h-12Zm6 4.5v10M13 7h2.5M13 17h2.5");
}

.ojjncdbgw {
  d: path("M2.5 16L4 17.5L5.5 16");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
