<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="aij9tdbqq"/><path class="rgqt8desf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:table-tree-fill" /></template>
<style>
.aij9tdbqq {
  fill: currentColor;
  d: path("M6 3H18C19.65685 3 21 4.34315 21 6V9H3V6C3 4.34315 4.34315 3 6 3Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rgqt8desf {
  d: path("M6 3H18C19.65685 3 21 4.34315 21 6V18C21 19.65685 19.65685 21 18 21H6C4.34315 21 3 19.65685 3 18V6C3 4.34315 4.34315 3 6 3ZM3 9H21M7 9V17H10M7 13H10M14 13H17M14 17H17");
}

</style>
