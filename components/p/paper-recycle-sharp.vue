<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="wdd_k9f2l"/><path class="xm-s5wboa"/><path class="g9zld1hdf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:paper-recycle-sharp" /></template>
<style>
.g9zld1hdf {
  d: path("M12.5 7v2.75h2.75M10.5 12.5h3m-3 2.5h3");
}

.wdd_k9f2l {
  d: path("M16.5 4.21a9 9 0 1 1-9 0m-.65 2.42l.65-2.42l-2.42-.65");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xm-s5wboa {
  d: path("M9.25 6.75h3.5l.71.71l1.58 1.58l.71.71v7.5h-7.5V6.75z");
}

</style>
