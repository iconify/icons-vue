<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="yhwu8cb8n"/><path class="v7jmcd5cn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:redox" /></template>
<style>
.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v7jmcd5cn {
  d: path("M19.75 6.75L18.5 9.5l-2.75-1.25");
}

.yhwu8cb8n {
  d: path("M3 16a3 3 0 1 0 6 0a3 3 0 1 0-6 0Zm12 0a3 3 0 1 0 6 0a3 3 0 1 0-6 0ZM5.5 9.5a7 7 0 0 1 13 0");
}

</style>
