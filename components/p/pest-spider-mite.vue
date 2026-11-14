<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="xbop7gbyo"/><path class="ky-d9tbad"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pest-spider-mite" /></template>
<style>
.ky-d9tbad {
  d: path("m9.75 7l-2.5-1.75v-2.5m2 6.25l-3.5-1L4 6.25m5.5 4.25l-3.5 1l-1.5 2m6-1.5l-1.75 1.25l-.25 1.25M14.25 7l2.5-1.75v-2.5m-2 6.25l3.5-1L20 6.25m-5.5 4.25l3.5 1l1.5 2m-6-1.5l1.75 1.25l.25 1.25");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xbop7gbyo {
  d: path("M2.5 19.5c4.5-3 13.5-3.25 19-1.5c-4.5 4-13.5 4.5-19 1.5ZM9.25 9a2.75 3.5 0 1 0 5.5 0a2.75 3.5 0 1 0-5.5 0Z");
}

</style>
