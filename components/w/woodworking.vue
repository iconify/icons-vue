<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="lqx7whxps"/><path class="nw66r3bzx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:woodworking" /></template>
<style>
.lqx7whxps {
  d: path("M2.5 14h19v5h-19Zm1 0L5 8.5h3.5L10 14m8.5 0v-1.75a1.5 1.5 0 0 1 3 0V14");
}

.nw66r3bzx {
  d: path("M12.5 14c0-6.5 3.5-10 6-9c2 .75 1 4-1.5 3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
