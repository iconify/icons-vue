<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="voduurnpi"/><path class="i45560cxr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:trending-up-fire" /></template>
<style>
.i45560cxr {
  d: path("M9.75 15.75L12 13.5l2.25 2.25");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.voduurnpi {
  d: path("M12 21.5c-4 0-7-2.75-7-6.5c0-4 3.5-6 4.5-10.5C11 6 12 7.75 12 10c1.5-.75 2.5-2 2.75-3.5c2.75 2 4.25 5 4.25 8.5c0 3.75-3 6.5-7 6.5Zm0-3v-5");
}

</style>
