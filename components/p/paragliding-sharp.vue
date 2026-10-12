<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="k2fl_sbqh"/><circle class="rip_g9cqu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:paragliding-sharp" /></template>
<style>
.k2fl_sbqh {
  d: path("M2.75 9.5c2-4.5 5.5-6.75 9.25-6.75S19.25 5 21.25 9.5C18.75 8 15.5 7.25 12 7.25S5.25 8 2.75 9.5Zm1 0L12 17m8.25-7.5L12 17");
}

.rip_g9cqu {
  cx: 12px;
  cy: 19.25px;
  r: 2px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
