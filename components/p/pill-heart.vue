<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="kpakp5byb"/><path class="ti-cpcbmk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pill-heart" /></template>
<style>
.kpakp5byb {
  d: path("m12 21l-8-8c-2.5-2.5-1.5-9 4-9c2 0 3.25 1.25 4 2.5c.75-1.25 2-2.5 4-2.5c5.5 0 6.5 6.5 4 9Z");
}

.ti-cpcbmk {
  d: path("M7.5 9.5h9v4h-9Zm4.5 0v4");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
