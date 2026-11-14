<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="l1xn5bc5a"/><path class="wmcwji7ui"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:risk-meter" /></template>
<style>
.l1xn5bc5a {
  d: path("M2.5 17a9.5 9.5 0 0 1 19 0M12 17l5-6");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wmcwji7ui {
  d: path("M10.5 17a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm-8 3.5h19");
}

</style>
