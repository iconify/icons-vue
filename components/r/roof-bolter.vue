<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="gvdnk_26s"/><path class="o80c4oval"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:roof-bolter" /></template>
<style>
.gvdnk_26s {
  d: path("M4.5 13.5h15a2 2 0 0 1 2 2v4a2 2 0 0 1-2 2h-15a2 2 0 0 1-2-2v-4a2 2 0 0 1 2-2Zm7.5 0V3M7 3h10");
}

.o80c4oval {
  d: path("M5.25 17.5a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0Zm11 0a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
