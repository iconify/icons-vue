<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="vkh2p_buw"/><path class="lokqr7bdh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:tutor-sharp" /></template>
<style>
.lokqr7bdh {
  d: path("M3.75 21.25v-4.5a3.75 3.75 0 0 1 7.5 0v4.5Zm10.25-10l2.153-.923L17.5 11.6l1.347-1.273L21 11.25v7l-2.153-.923L17.5 18.6l-1.347-1.273L14 18.25Zm3.5.35v7");
}

.vkh2p_buw {
  cx: 7.5px;
  cy: 7px;
  r: 2.75px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
