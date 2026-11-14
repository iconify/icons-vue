<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="sjgu_obyo"/><path class="oycpyu9gq"/><path class="yheiu4i6w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:orange-tree" /></template>
<style>
.oycpyu9gq {
  fill: currentColor;
  d: path("M8.25 7.5a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0Zm5.5 1.5a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0Zm-4 4a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0Z");
}

.sjgu_obyo {
  d: path("M4.5 9.5a7.5 7.5 0 1 0 15 0a7.5 7.5 0 1 0-15 0ZM12 17v4.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yheiu4i6w {
  d: path("M8.5 21.5h7");
}

</style>
