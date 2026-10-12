<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="p60z1pq9y"/><circle class="cey46ju5m"/><path class="denqkxbyj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:quarantine-sign-sharp" /></template>
<style>
.cey46ju5m {
  cx: 12px;
  cy: 9px;
  r: 2.25px;
}

.denqkxbyj {
  d: path("M12 4.75v1m0 6.5v1M7.75 9h1m6.5 0h1M9 6l.7.7M15 6l-.7.7M9 12l.7-.7m5.3.7l-.7-.7");
}

.p60z1pq9y {
  d: path("M2.75 3.25h18.5v11.5H2.75zm4.75 11.5v6.5m9-6.5v6.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
