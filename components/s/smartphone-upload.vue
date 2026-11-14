<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="sb0axvnbu"/><path class="ymm7jyq0l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:smartphone-upload" /></template>
<style>
.sb0axvnbu {
  d: path("M6 2.5h12v19H6ZM10.5 18h3M12 11.5V6");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ymm7jyq0l {
  d: path("M9.5 8.5L12 6l2.5 2.5m-5.5 6h6");
}

</style>
