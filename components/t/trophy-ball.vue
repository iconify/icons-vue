<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="oefbiufcj"/><path class="bk6pd9_5p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:trophy-ball" /></template>
<style>
.bk6pd9_5p {
  d: path("M6.5 11.5c-3.5 0-3 4 1 3.5m10-3.5c3.5 0 3 4-1 3.5M12 17.5v4m-3.5 0h7M9.5 4q2.5 2.5 5 0");
}

.oefbiufcj {
  d: path("M9.25 5a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0ZM6.5 10.5h11V12a5.5 5.5 0 0 1-11 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
