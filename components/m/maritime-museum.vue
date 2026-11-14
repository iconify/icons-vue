<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="p9syo4thx"/><path class="c_w47e8ds"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:maritime-museum" /></template>
<style>
.c_w47e8ds {
  d: path("M12 14.75V8.5l4 3.5h-4m-5.5 2.75h11l-1.75 2.75h-7.5Z");
}

.p9syo4thx {
  d: path("m3.5 9.5l8.5-6l8.5 6v11h-17Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
