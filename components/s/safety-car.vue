<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="qjt-nxbgo"/><path class="v2sbl0cwb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:safety-car" /></template>
<style>
.qjt-nxbgo {
  d: path("M2.5 15.25v-2.5a1.5 1.5 0 0 1 1.5-1.5l3-.5l2.5-3H15l3 3l2 .5a1.5 1.5 0 0 1 1.5 1.5v2.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v2sbl0cwb {
  d: path("M4.5 17.75a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm10 0a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0ZM9.75 3h5v2h-5Z");
}

</style>
