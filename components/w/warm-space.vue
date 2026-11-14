<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ozif9d10d"/><path class="x6h3rsbnp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:warm-space" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ozif9d10d {
  d: path("M12.951 21.5H5.5q-.098 0-.196-.01q-.098-.009-.194-.028q-.097-.02-.191-.048q-.094-.029-.184-.066q-.091-.038-.178-.084q-.086-.046-.168-.101t-.158-.117t-.145-.132q-.07-.069-.132-.145t-.117-.158t-.101-.168t-.084-.178q-.037-.09-.066-.184q-.028-.094-.048-.191q-.019-.096-.028-.194T3.5 19.5V10L12 3l8.5 7v2.977");
}

.x6h3rsbnp {
  d: path("M16.25 6.5v-3h2.5v5m-.75 13c-1.75 0-3-1.25-3-3s1.75-2.5 2-4.25C18 15 18.5 16 18.5 17q.75-.75.75-1.5c1.25 1 1.75 2 1.75 3c0 1.75-1.25 3-3 3");
}

</style>
