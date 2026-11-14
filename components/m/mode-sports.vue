<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="stjdzlbin"/><path class="h-3tp7bgo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:mode-sports" /></template>
<style>
.h-3tp7bgo {
  d: path("M15.5 8.5L13 14l3 3v4m-3-7l-1.5 3L9 18.5M3.5 10h4m-4 4H8");
}

.stjdzlbin {
  d: path("M15.25 4a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Zm-4.75 7L13 8.5h3.5l2.5 3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
