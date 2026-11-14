<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="rh4hqugip"/><path class="sx1egnbrw"/><path class="h59y9_xcz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pdc-drill-bit" /></template>
<style>
.h59y9_xcz {
  fill: currentColor;
  d: path("M12 5h.01M12 7.5h.01m6.052 8h.01m-2.175-1.25h.01M5.938 15.5h.01m2.155-1.25h.01");
}

.rh4hqugip {
  d: path("M2 12a10 10 0 1 0 20 0a10 10 0 1 0-20 0Z");
}

.sx1egnbrw {
  d: path("M9.75 12a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0Zm0-9.25h4.5V9.5h-4.5Zm11.386 11.926l-2.25 3.898l-5.846-3.375l2.25-3.898ZM5.114 18.574l-2.25-3.898l5.846-3.375l2.25 3.898Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
