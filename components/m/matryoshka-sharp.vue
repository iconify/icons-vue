<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="q7xm6-okb"/><circle class="no-xaab-v"/><path class="bnm3dlbpz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:matryoshka-sharp" /></template>
<style>
.bnm3dlbpz {
  d: path("m8.5 13.5l3.5 2.188l3.5-2.188M12 16.25v2.5");
}

.no-xaab-v {
  cx: 12px;
  cy: 6.5px;
  r: 1.25px;
}

.q7xm6-okb {
  d: path("M12 2.75A3.75 3.75 0 0 0 8.25 6.5v1.24l.8.96C7 10 5.75 12.5 5.75 15.5c0 3.5 2 5.75 6.25 5.75s6.25-2.25 6.25-5.75c0-3-1.25-5.5-3.3-6.8l.8-.96V6.5A3.75 3.75 0 0 0 12 2.75Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
