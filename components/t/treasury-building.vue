<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="it2ofsboz"/><path class="jx6p4pcxz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:treasury-building" /></template>
<style>
.it2ofsboz {
  d: path("M2.5 4.5h11v13h-11Zm2.5 13v2m6-2v2m5.25-10h5.25v10h-5.25Z");
}

.jx6p4pcxz {
  d: path("M5.25 11a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0Zm11 1.75h5.25m-5.25 3.5h5.25");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
