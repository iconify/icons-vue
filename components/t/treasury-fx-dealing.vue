<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="a1e75ubos"/><path class="ygrug_jay"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:treasury-fx-dealing" /></template>
<style>
.a1e75ubos {
  d: path("M2.5 2.5h19v14h-19Zm9.5 14v4m-3.5 0h7m-9-13.25H17");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ygrug_jay {
  d: path("M15.25 5.5L17 7.25L15.25 9m2.25 2.75H7M8.75 10L7 11.75l1.75 1.75");
}

</style>
