<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zsue4nw4g"/><path class="ae7jawb8g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:notice-period" /></template>
<style>
.ae7jawb8g {
  d: path("m2.5 2.5l4 2v15l-4 2Zm10 12.75a4.5 4.5 0 1 0 9 0a4.5 4.5 0 1 0-9 0ZM17 8v2.75M15.5 8h3M17 15.25v-2.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zsue4nw4g {
  d: path("M2.5 21.5v-18a1 1 0 0 1 1-1h5a1 1 0 0 1 1 1v18");
}

</style>
