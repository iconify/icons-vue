<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ckt283erw"/><path class="sqh_rpcvm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pergola-vines" /></template>
<style>
.ckt283erw {
  d: path("M6 21V10a6 6 0 0 1 12 0v11");
}

.sqh_rpcvm {
  d: path("M6 17c1-2.5 3.5-3.25 5-2.75c-.5 2.25-3 3.5-5 2.75Zm.75-10c-1.25-2-3-2.75-4.25-2.5c.5 2 2.25 3 4.25 2.5ZM18 12.5c.75-2.25 2.25-3.25 3.5-3c-.25 2.25-1.75 3.5-3.5 3Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
