<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hlxgrbb-p"/><path class="xo1ijgcab"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:smart-casual" /></template>
<style>
.hlxgrbb-p {
  d: path("M8 3L4 5c-.6.3-1 1-1 1.75V20c0 .75.75 1.5 1.5 1.5h15c.75 0 1.5-.75 1.5-1.5V6.75C21 6 20.6 5.3 20 5l-4-2");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xo1ijgcab {
  d: path("M8 3L6.5 7.5l2 1.5l3.5 6.5M16 3l1.5 4.5l-2 1.5l-3.5 6.5m0 0v6");
}

</style>
