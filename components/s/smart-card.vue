<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hn7tnnbwb"/><path class="oo5a6jbdh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:smart-card" /></template>
<style>
.hn7tnnbwb {
  d: path("M2.5 5h19v14h-19Z");
}

.oo5a6jbdh {
  d: path("M5.5 9h5v4h-5Zm8 1h5m-5 3.5H17");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
