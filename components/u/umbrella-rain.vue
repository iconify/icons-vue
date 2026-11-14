<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="uzq27-naf"/><path class="yrtd6kb7a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:umbrella-rain" /></template>
<style>
.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.uzq27-naf {
  d: path("M3.5 15.5a8.5 8.5 0 0 1 17 0q-2.75-1.75-5.75 0q-2.75-1.75-5.5 0q-3-1.75-5.75 0Z");
}

.yrtd6kb7a {
  d: path("M12 14.75v4.75a1.75 1.75 0 0 1-3.5 0M6 2.5L5.25 5m7.25-2.5L12 4.25m6.75-1.75L18 5");
}

</style>
