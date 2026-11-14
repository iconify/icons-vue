<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="yshzrjs_x"/><path class="vb3dxjvnw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:robotic-arm-picking" /></template>
<style>
.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vb3dxjvnw {
  d: path("M6.5 10a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0ZM18 9.5V13m-1.5 0h3");
}

.yshzrjs_x {
  d: path("M4 17h8v3.5H4Zm4 0v-7l6-4m0 0l4 3.5");
}

</style>
