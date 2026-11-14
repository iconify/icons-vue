<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="dkebj3bea"/><path class="saglq1sqe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:toggle-check" /></template>
<style>
.dkebj3bea {
  d: path("M6 6.5h12a3.5 3.5 0 0 1 3.5 3.5v4a3.5 3.5 0 0 1-3.5 3.5H6A3.5 3.5 0 0 1 2.5 14v-4A3.5 3.5 0 0 1 6 6.5Z");
}

.saglq1sqe {
  d: path("M13 12a3 3 0 1 0 6 0a3 3 0 1 0-6 0Zm-7.25 0L7 13.25l2.25-2.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
