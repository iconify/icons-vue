<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="k-uw7kbev"/><path class="kvklp-zfy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:sql-injection-sharp" /></template>
<style>
.k-uw7kbev {
  d: path("M2.75 6C2.75 4.2 5.1 2.75 8 2.75S13.25 4.2 13.25 6v11.5c0 1.8-2.35 3.25-5.25 3.25S2.75 19.3 2.75 17.5Z");
}

.kvklp-zfy {
  d: path("M2.75 6C2.75 7.8 5.1 9.25 8 9.25S13.25 7.8 13.25 6m-10.5 5.75C2.75 13.55 5.1 15 8 15s5.25-1.45 5.25-3.25m5.93-5.87l-1.06-1.06l-.53-.53l-.53.53l-1.09 1.09l-.53.53l.53.53l1.06 1.06l.53.53l.53-.53l1.09-1.09l.53-.53zm-.53-.53l1.6-1.6m-1-1l2 2M16.5 7.5l-4 4");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
