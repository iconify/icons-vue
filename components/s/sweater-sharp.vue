<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="fi4giqd8r"/><path class="nk1wq05rf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:sweater-sharp" /></template>
<style>
.fi4giqd8r {
  d: path("M9.75 3.25h5.75l1.1.58l2.05 1.09l1.1.58l.13 1.24l1.24 12.02l.13 1.24l-1.22.26l-1.06.23q-1.22.26-2.47.26h-9q-1.25 0-2.47-.26l-1.06-.23L2.75 20l.13-1.24L4.12 6.74l.13-1.24l1.1-.58L7.4 3.83l1.1-.58z");
}

.nk1wq05rf {
  d: path("M9.25 3.5a2.75 2.25 0 0 0 5.5 0M8 18v2.75M12 18v2.75M16 18v2.75");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
