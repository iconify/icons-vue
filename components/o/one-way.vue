<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jel3h_b-a"/><path class="ujny1bbix"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:one-way" /></template>
<style>
.jel3h_b-a {
  d: path("M2.5 3h19v10h-19ZM12 13v8M6.5 8h10.25");
}

.ujny1bbix {
  d: path("M14.5 5.75L16.75 8l-2.25 2.25");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
