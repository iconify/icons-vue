<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="h-o5e7bwo"/><path class="hpcy_xbqs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pores" /></template>
<style>
.h-o5e7bwo {
  d: path("M12 2.5c6 0 9.5 3.5 9.5 9.5S18 21.5 12 21.5S2.5 18 2.5 12S6 2.5 12 2.5Z");
}

.hpcy_xbqs {
  d: path("M5.75 9a3 2.25 0 1 0 6 0a3 2.25 0 1 0-6 0Zm7 3.25a2.5 1.75 0 1 0 5 0a2.5 1.75 0 1 0-5 0Zm-5 4a2 1.5 0 1 0 4 0a2 1.5 0 1 0-4 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
