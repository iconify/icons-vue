<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="db_lt25qf"/><path class="jfv_jd2bm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:treasure-chest-lock-sharp" /></template>
<style>
.db_lt25qf {
  d: path("M7.25 4H21v17H3V4zM3 10.75h5m8 0h5");
}

.jfv_jd2bm {
  d: path("M10.25 8.75h3.5v4.5h-3.5z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
