<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="qu9nn5egh"/><path class="cshjojgyj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:speech-recognition" /></template>
<style>
.cshjojgyj {
  d: path("M6.25 10.5a5.75 5.75 0 0 0 11.5 0M12 16.25V21M4 6.5a6 6 0 0 0 0 7m16-7a6 6 0 0 1 0 7");
}

.qu9nn5egh {
  d: path("M10 2.5h4a1 1 0 0 1 1 1v9a1 1 0 0 1-1 1h-4a1 1 0 0 1-1-1v-9a1 1 0 0 1 1-1Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
