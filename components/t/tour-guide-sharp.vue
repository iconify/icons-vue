<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="cnliououd"/><path class="ak8kv4b8p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:tour-guide-sharp" /></template>
<style>
.ak8kv4b8p {
  d: path("M3 21.25V18a5.5 5.5 0 0 1 11 0v3.25ZM13.25 15l4.25-2.25m0 8.5v-15m.45-3.29l2.85 1.33l.45.21l-.45.21l-2.85 1.33l-.45.21v-3.5z");
}

.cnliououd {
  cx: 8.5px;
  cy: 7.25px;
  r: 3px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
