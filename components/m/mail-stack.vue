<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="majqov-ge"/><path class="jg7dhrbvi"/><path class="zf0ibxbza"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:mail-stack" /></template>
<style>
.jg7dhrbvi {
  d: path("M5.5 4.5h14a2 2 0 0 1 2 2v10");
}

.majqov-ge {
  d: path("M2.5 7.5h16V20h-16Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zf0ibxbza {
  d: path("m6 11l4.5 3l4.5-3");
}

</style>
