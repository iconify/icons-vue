<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="g59h5vblh"/><path class="n8bfjv0rg"/><path class="ufhdbwbcs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:stem-cell" /></template>
<style>
.g59h5vblh {
  d: path("M2.5 12a4.5 4.5 0 1 0 9 0a4.5 4.5 0 1 0-9 0Z");
}

.n8bfjv0rg {
  fill: currentColor;
  d: path("M5.5 12a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Z");
}

.ufhdbwbcs {
  d: path("m11.75 9.5l3-3M13 6.25l1.75.25v1.75M12.25 12H15m-1.5-1.5L15 12l-1.5 1.5m-1.75 1l3 3m-1.75.25l1.75-.25v-1.75M17 4.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm.25 5.5h4.25v4h-4.25ZM17 19.5a2.25 1.75 0 1 0 4.5 0a2.25 1.75 0 1 0-4.5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
