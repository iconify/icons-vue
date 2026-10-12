<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="guc4fjbhq"/><path class="o2x6yybsc"/><path class="oxw7akivi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:prompt-chain-sharp" /></template>
<style>
.guc4fjbhq {
  d: path("M2.75 3.25h11v6.5h-11z");
}

.o2x6yybsc {
  d: path("m5.75 5l1.5 1.5L5.75 8m2.5 1.75v7.5h2m0-3h11v6.5h-11z");
}

.oxw7akivi {
  d: path("m13.25 16l1.5 1.5l-1.5 1.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
