<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="mtx364rzr"/><path class="wm-zc7p3r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:notebook-ai" /></template>
<style>
.mtx364rzr {
  d: path("M19.5 21.3v.2h-15v-19h15v12.2M2.5 7h4m-4 5h4m-4 5h4");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wm-zc7p3r {
  d: path("M18 14.75C18 17 19 18 21.25 18C19 18 18 19 18 21.25C18 19 17 18 14.75 18C17 18 18 17 18 14.75Z");
}

</style>
