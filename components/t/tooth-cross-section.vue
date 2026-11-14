<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="dz_qwxbde"/><path class="v-7fa-hlo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:tooth-cross-section" /></template>
<style>
.dz_qwxbde {
  d: path("M7 3C4.5 3 3.5 5 3.5 7.5c0 3 1.5 4.5 2 6.5l1.25 6c.25 1.25 1.75 1.25 2 0L10 15.5c.5-1.5 3.5-1.5 4 0l1.25 4.5c.25 1.25 1.75 1.25 2 0l1.25-6c.5-2 2-3.5 2-6.5C20.5 5 19.5 3 17 3c-2 0-3 1.25-5 1.25S9 3 7 3Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v-7fa-hlo {
  d: path("M8 11V8.5c0-1.5 1-1.75 2-1L12 9l2-1.5c1-.75 2-.5 2 1V11c0 .75-.5 1-1.25 1h-5.5C8.5 12 8 11.75 8 11Z");
}

</style>
