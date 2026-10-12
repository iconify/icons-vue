<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="ye0axzb1w"/><path class="qux1fbbed"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:user-graduate-sharp" /></template>
<style>
.qux1fbbed {
  d: path("M6 20.25h12.75v-.75c0-2.2-3.04-3.75-6.75-3.75S5.25 17.3 5.25 19.5v.75zm6.56-17.28l7.63 3.06l.56.22l-.56.22l-7.63 3.06l-.56.22l-.56-.22l-7.63-3.06l-.56-.22l.56-.22l7.63-3.06l.56-.22zm8.19 3.53v3.75");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ye0axzb1w {
  cx: 12px;
  cy: 10.25px;
  r: 3px;
}

</style>
