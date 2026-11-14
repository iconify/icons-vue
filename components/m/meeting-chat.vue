<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="gyxdmb1sy"/><path class="xzxzovbav"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:meeting-chat" /></template>
<style>
.gyxdmb1sy {
  d: path("M9.7 14.5H2.5v-11h14v5.7");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xzxzovbav {
  d: path("M8 6.5L12 9l-4 2.5Zm4.5 7.5a2 2 0 0 1 2-2h5a2 2 0 0 1 2 2v3a2 2 0 0 1-2 2H16l-3.5 2.5Z");
}

</style>
