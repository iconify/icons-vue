<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="wz-2abclz"/><path class="s1yv7xbwz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:panorama-sharp" /></template>
<style>
.s1yv7xbwz {
  d: path("m7 14.5l3-3l2.25 2.25L14 12l2.75 2.75");
}

.wz-2abclz {
  d: path("m2.75 8.25l.005-1.357L4.05 7.3q7.95 2.4 15.9 0l1.295-.407l.005 1.357v7.5l-.005 1.357l-1.295-.407q-7.95-2.4-15.9 0l-1.295.407l-.005-1.357Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
