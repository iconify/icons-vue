<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="gd2-xmvhk"/><path class="m3sf1bbag"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:trash-chute" /></template>
<style>
.gd2-xmvhk {
  d: path("M5.5 4h13v9h-13Z");
}

.m3sf1bbag {
  d: path("M5.5 13h13L20 7H4ZM10 9.75h4m-2 5.75V21m-2.5-2.5L12 21l2.5-2.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
