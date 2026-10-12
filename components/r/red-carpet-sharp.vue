<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="z_dmbrb2g"/><path class="d4ee3cr2h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:red-carpet-sharp" /></template>
<style>
.d4ee3cr2h {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3.25 9.5h.01m17.49 0h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.z_dmbrb2g {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.6 8.5H14l.2.57l4.1 11.61l.2.57h-13l.2-.57L9.8 9.07l.2-.57zM3.25 21.25V11.5m17.5 9.75V11.5m-17.5 1l1.793 3.228L7.5 14.5m13.25-2l-1.793 3.228L16.5 14.5");
}

</style>
