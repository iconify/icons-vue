<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="w_3_fcchr"/><path class="gs-jy0aiz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:volume-measure-cube" /></template>
<style>
.gs-jy0aiz {
  d: path("m4 7l8 4.5L20 7m-8 4.5v10m-8-9l8 4.5l8-4.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.w_3_fcchr {
  d: path("M12 2.5L20 7v10l-8 4.5L4 17V7Z");
}

</style>
