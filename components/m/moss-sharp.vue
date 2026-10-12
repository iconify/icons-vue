<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="qxb5_qb0x"/><path class="e5piu6b3i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:moss-sharp" /></template>
<style>
.e5piu6b3i {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6.25 10h.01m6.99-4.5h.01m4.49 3h.01");
}

.qxb5_qb0x {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 20.25c0-2.75 2.75-4.75 6-4.75h6.5c3.25 0 6 2 6 4.75v1H2.75zM7.5 15.5v-5.083L6.25 10M12 15.5V5.917l1.25-.417m3.25 10V8.917l1.25-.417");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
