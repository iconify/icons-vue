<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="dxilmz-8r"/><path class="k-3ur3bth"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:rx-auto-refill" /></template>
<style>
.dxilmz-8r {
  d: path("M12 3.5a8.5 8.5 0 1 1-6.01 2.49");
}

.k-3ur3bth {
  d: path("M2.75 6H6v3.25M9.75 7h4.5v2h-4.5ZM9 9h6v7.5H9Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
