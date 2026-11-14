<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="t99mkzbow"/><path class="xu44crb8e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:women-football" /></template>
<style>
.t99mkzbow {
  d: path("M5 7a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xu44crb8e {
  d: path("M11.5 5.25c3-.25 4 2.75 2.75 5.25M2.5 21c0-4 2.5-6.5 6-6.5c.896 0 1.726.164 2.466.475M13 17.5a4.5 2.75 0 1 0 9 0a4.5 2.75 0 1 0-9 0Zm3.25 1.25l2.5-2.5");
}

</style>
