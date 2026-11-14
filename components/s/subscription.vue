<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ctq0t5yes"/><path class="vhrqxgm1n"/><path class="jo9-w8fga"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:subscription" /></template>
<style>
.ctq0t5yes {
  d: path("M5.938 8.5A7 7 0 0 1 19 12");
}

.jo9-w8fga {
  d: path("M7.5 14.5L5 12l-2.5 2.5m11.25-4.25C13.5 9.5 12.9 9 12 9c-1.05 0-1.75.6-1.75 1.5c0 1.6 3.5.9 3.5 3c0 .9-.75 1.5-1.75 1.5c-.9 0-1.55-.4-1.75-1M12 7.75V9m0 6v1.25");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vhrqxgm1n {
  d: path("M16.5 9.5L19 12l2.5-2.5m-3.438 6A7 7 0 0 1 5 12");
}

</style>
