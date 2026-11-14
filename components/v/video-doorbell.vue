<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="cb-52l0ci"/><path class="cbaqxizmc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:video-doorbell" /></template>
<style>
.cb-52l0ci {
  d: path("M10 2.5h4a3 3 0 0 1 3 3v13a3 3 0 0 1-3 3h-4a3 3 0 0 1-3-3v-13a3 3 0 0 1 3-3Z");
}

.cbaqxizmc {
  d: path("M9.5 8a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0ZM12 8h.01M10 15.75a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
