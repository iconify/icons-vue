<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="d3yh5cbqf"/><path class="t6-ywobow"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:masala-dabba-sharp" /></template>
<style>
.d3yh5cbqf {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 4.5h.01");
}

.t6-ywobow {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 7h18M4 10h16v10H4z");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
