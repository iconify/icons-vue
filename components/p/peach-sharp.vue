<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="tyx_psbxo"/><path class="nvyohixgh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:peach-sharp" /></template>
<style>
.nvyohixgh {
  d: path("M12 9V6.667L13 5m0 0c1-1.75 3-2.5 5.75-1.75c-1 2.25-3 3-5.75 1.75Zm-1 5c-1.75 2.5-2 6 0 9.5");
}

.tyx_psbxo {
  d: path("M12 9L9.917 7.75H7.75c-2.75 0-4.5 2.5-4.5 5.75C3.25 18 7 21.25 12 21.25s8.75-3.25 8.75-7.75c0-3.25-1.75-5.75-4.5-5.75h-2.167z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
