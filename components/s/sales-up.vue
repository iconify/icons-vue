<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="e5vwbp-fb"/><path class="vrgdw8bti"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:sales-up" /></template>
<style>
.e5vwbp-fb {
  d: path("M7 20.5V17m5 3.5V14m5 6.5V11M4 13l5-5l3.5 2.5l7-7");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vrgdw8bti {
  d: path("M15 3.5h4.5V8");
}

</style>
