<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="weez58bvj"/><path class="k496qzbil"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pin-airport" /></template>
<style>
.k496qzbil {
  d: path("M12 5.5c.5 0 .75.5.75 1V8l2.75 1.5v1l-2.75-.75v1.75l1 .5v.75l-1.75-.5l-1.75.5V12l1-.5V9.75l-2.75.75v-1L11.25 8V6.5c0-.5.25-1 .75-1Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.weez58bvj {
  d: path("M12 21.5S4.5 15 4.5 9.5a7.5 7.5 0 0 1 15 0c0 5.5-7.5 12-7.5 12Z");
}

</style>
