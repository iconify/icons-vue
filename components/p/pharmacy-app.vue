<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="dxsxh5xhc"/><path class="rmvrhbcuk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pharmacy-app" /></template>
<style>
.dxsxh5xhc {
  d: path("M6 2.5h12v19H6Z");
}

.rmvrhbcuk {
  d: path("m13.414 7.757l2.829 2.829l-5.657 5.657l-2.829-2.829Zm-2.828 2.829l2.828 2.828M10.5 18.5h3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
