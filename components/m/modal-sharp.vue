<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="pw7p-85ys"/><path class="kv_1swb1n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:modal-sharp" /></template>
<style>
.kv_1swb1n {
  d: path("M6 7.5h12v10H6zm.75 3.25h10.5m-2.5-2L16 10m0-1.25L14.75 10");
}

.pw7p-85ys {
  d: path("M2.75 3.75h18.5v16.5H2.75z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
